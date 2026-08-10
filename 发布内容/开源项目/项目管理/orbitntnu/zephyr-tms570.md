# zephyr-tms570

> 板块：项目管理 / OrbitNTNU
> 来源：https://github.com/OrbitNTNU/zephyr-tms570
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

zephyr-tms570 是 OrbitNTNU 团队为 TI TMS570 星载 SoC 提供的 Zephyr RTOS 移植，使 Zephyr 能够运行在这款常用于小卫星的安全关键处理器上。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/OrbitNTNU/zephyr-tms570.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `zephyr-tms570` |
| 项目标识 | `zephyr-tms570` |
| 项目简介 | 为 TI TMS570 星载 SoC 提供的 Zephyr RTOS 移植（OrbitNTNU），使 Zephyr 可运行于小卫星常用安全关键处理器。镜像收录自 https://github.com/OrbitNTNU/zephyr-tms570，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 操作系统 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「操作系统」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规
