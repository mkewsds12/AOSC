# TorchGeo · GitLink 社区镜像组织

> 来源：<https://github.com/torchgeo>
> 定位：在 GitLink 建立「TorchGeo」的国内社区镜像组织，批量镜像其开源仓库
> 状态：已发布

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
| :--- | :--- |
| 组织账号 | `torchgeo`（若提示已被占用，改用 `torchgeo-mirror`） |
| 组织名称 | `TorchGeo（社区镜像）` |
| 组织描述 | TorchGeo 开源项目的非官方社区镜像，仅收录 TorchGeo 公开发布的开源项目；版权归原作者与来源组织（<https://github.com/torchgeo>）；仓库以只读镜像方式同步，每 8 小时更新一次。 |
| 所在地区 | 可留空或按项目背景填写 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | Stars | 镜像可行性 |
| :--- | :--- | :--- | :--- | :--- |
| torchgeo | [torchgeo.md](torchgeo.md) | MIT | 4139 | ✅ 可镜像 |
| terratorch | [terratorch.md](terratorch.md) | Apache-2.0 | 841 | ✅ 可镜像 |
| terrakit | [terrakit.md](terrakit.md) | Apache-2.0 | 43 | ✅ 可镜像 |
| torchgeo-bench | [torchgeo-bench.md](torchgeo-bench.md) | MIT | 24 | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类（本项目方向统一归「算法处理」）

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- torchgeo / torchgeo-bench / ssl4eo-l / tsas-paper 为 MIT，terratorch / terrakit 为 Apache-2.0，均可合规镜像
- 其余仓库（torchgeo.github.io 文档站、governance 治理文档、ssl4eo-l / tsas-paper 论文复现代码）为非核心代码，暂不纳入镜像清单

## 五、组织背景（供简介/新闻引用）

TorchGeo 是面向地理空间数据的 PyTorch 深度学习工具库，由微软开源生态与学术社区共建，官网 <https://torchgeo.org> 。提供遥感数据集加载、采样器、数据变换与预训练模型，是遥感 AI 领域使用最广泛的开源基础库之一（主仓库 4.1k+ star）。生态还包括 TerraTorch（地理空间基础模型微调）、TerraKit（ML-ready 数据集构建）与 TorchGeo-Bench（标准基准评测）。本组织将 TorchGeo 生态纳入「算法处理」分类，作为星上/地面遥感智能处理方向的重要参考。

## 状态流转

- 状态：已发布（本文件夹位于 开源项目/已发布/）
- GitLink 建组织、镜像导入、专区上架已完成
- 调研日期：2026-08-11（GitHub API 复核，8 个公开仓库）
