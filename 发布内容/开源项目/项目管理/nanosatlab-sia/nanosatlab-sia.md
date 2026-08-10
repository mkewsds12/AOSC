# NanosatLab-SIA

> 板块：项目管理 / NanosatLab-SIA
> 来源：https://github.com/NanosatLab-SIA
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

西班牙 SIA 纳星实验室（NanosatLab-SIA）的开源组织主页，公开其纳卫星星载软件栈，重点包括基于 Toradex 平台的星载 Linux/u-boot BSP 等板级支持包。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页（https://github.com/NanosatLab-SIA），无法整体镜像，需按下方列出的重点仓库逐个导入（仓库名以实际为准） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NanosatLab-SIA` |
| 项目标识 | `nanosatlab-sia` |
| 项目简介 | 西班牙 SIA 纳星实验室开源组织主页，公开纳卫星星载软件栈，重点为基于 Toradex 平台的星载 Linux/u-boot BSP。镜像收录自 https://github.com/NanosatLab-SIA，License：各重点仓库分别核查，见文末许可证核查节 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 操作系统 |
| 项目语言 | 以源仓库为准 |

## 重点仓库列表（需逐个镜像导入，仓库名以实际为准）

| 仓库名 | URL |
|--------|-----|
| 星载 Linux BSP（Toradex，需人工确认仓库名） | https://github.com/NanosatLab-SIA/linux-toradex |
| u-boot BSP（需人工确认仓库名） | https://github.com/NanosatLab-SIA/u-boot-toradex |

> 以上为按「组织地址/仓库名」拼出的候选地址，导入前需在组织主页人工确认实际仓库名。

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「操作系统」→ 保存

## 许可证核查（2026-08-10）

| 仓库 | 结果 |
|------|------|
| NanosatLab-SIA/linux-toradex | GPL-2.0（Linux 内核 COPYING，master 分支），可镜像 |
| NanosatLab-SIA/u-boot-toradex | GPL-2.0（U-Boot COPYING，2011.12-colibri_vf 分支），可镜像 |

- 结论：许可证明确，可镜像；镜像时保留 COPYING 与版权声明。GPL-2.0：衍生/分发需开源同等授权；镜像只读展示合规
