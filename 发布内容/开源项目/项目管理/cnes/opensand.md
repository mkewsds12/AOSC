# CNES OpenSand

> 板块：项目管理 / cnes
> 来源：https://github.com/CNES/opensand
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

OpenSand 是法国国家空间研究中心（CNES）开源的卫星通信网络仿真器，可仿真完整的卫星通信系统，包括网关、终端与卫星转发器，支持 DVB-S2/RCS2 体制，用于卫星通信网络协议验证、性能评估与测试床搭建。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/CNES/opensand.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `CNES OpenSand` |
| 项目标识 | `opensand` |
| 项目简介 | CNES 开源的卫星通信网络仿真器，可仿真含网关、终端、转发器的完整卫星通信系统，支持 DVB-S2/RCS2 体制，用于协议验证、性能评估与测试床搭建。镜像收录自 https://github.com/CNES/opensand，License：未检测到 LICENSE 文件 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：⚠️ 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYING.md/COPYRIGHT/UNLICENSE，main/master 分支；仓库本身可访问）
- 结论：**不可镜像代码**。公开仓库不等于授权，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
