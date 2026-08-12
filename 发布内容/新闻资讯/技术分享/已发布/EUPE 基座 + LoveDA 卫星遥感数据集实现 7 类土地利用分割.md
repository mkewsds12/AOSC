# EUPE 基座 + LoveDA 卫星遥感数据集实现 7 类土地利用分割

> 栏目：技术分享
> 状态：已发布
> 作者：吃着橙子的猫
> 来源：学习算法的猫
> 发布时间：2026-08-11

## 正文

遥感语义分割有一个尴尬的局面：大模型效果虽好，但动不动几百 M 参数，放到卫星上是不可能的任务；轻量模型倒是能跑，精度又差一截。本项目走了一条高性价比路线：

- 直接搬出 Meta 最新开源的通用视觉编码器 EUPE ViT-B 当做眼睛；
- 训练时冻结基座权重，每个场景只在上层挂载一个轻量解码头（参数量相比完整分割模型小一个数量级），只学"怎么读出眼睛看到的信息"；
- EUPE 通过蒸馏多个领域专家模型，具备极强的通用表征能力，提取的特征质量有充分保障；
- 而解码头加起来参数量不到 0.5M，只负责"如何读出眼睛看到的东西"。

数据集用的是 LoveDA——由武汉大学发布的土地利用分割数据集，包含 5987 张 1024×1024 的 0.3m 高分辨率 RGB 影像，没有近红外。

SegFormerMLPHead 仅训练 13 轮（总共 40 轮）即收敛至最佳——mIoU 0.551，Pixel Accuracy 0.729。作为对比，LoveDA 原论文（NeurIPS 2021）中 FCN、PSPNet、DeepLabV3+、UNet 等主流语义分割方法在域适应设置下 mIoU 普遍集中在 40%~50% 区间——冻结 EUPE 基座 + 轻量级渐进式解码头这条路，参数少一个数量级，精度、训练成本、边缘部署成本反而更有竞争力。

**SegFormerMLPHead —— Channel Concat 平铺融合 + 渐进式上采样细化**

- ViT 各层输出空间分辨率相同（都是 patch 下采样后的尺寸），直接把四层特征 Channel Concat 到一起；
- 一个 3×3 Conv 融合后，进行四级渐进 2× 上采样；
- SeparableConvBlock 是 3×3 Depthwise → BN → GELU → 1×1 Pointwise → BN → GELU，在放大过程中"雕刻"地物边界。

以下为 SegFormerMLPHead 在 LoveDA 验证集上各分类的 IoU：

<!-- 配图：LoveDA 验证集各分类 IoU 表格 -->

**分析：**

- 水体 IoU 最高（0.719）：因为 RGB 影像中水体呈暗色调，与周围陆地对比度最大，分割边界最干净；
- 裸地垫底（0.300）：主要原因在于数据集仅有三波段 RGB，裸土与刚翻过的农田在可见光波段光谱高度相似。

LoveDA（A Remote Sensing Land-Cover Dataset for Domain Adaptive Semantic Segmentation）由武汉大学发布（NeurIPS 2021 Datasets and Benchmarks），专为域自适应土地利用分割设计。核心特点：包含城市（Urban）和乡村（Rural）。

**参考论文：**

LoveDA: A Remote Sensing Land-Cover Dataset for Domain Adaptive Semantic Segmentation. Wang J, Zheng Z, Ma A, et al. NeurIPS Datasets and Benchmarks, 2021. https://arxiv.org/abs/2110.08733

来源：学习算法的猫
