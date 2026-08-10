# Zephyr RTOS

> 板块：项目管理 / zephyrproject-rtos
> 来源：https://github.com/zephyrproject-rtos/zephyr
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Zephyr 是 Linux 基金会托管的嵌入式实时操作系统（RTOS），支持多种架构、具备可裁剪内核与丰富驱动生态，在星载嵌入式场景应用广泛（如 FINCH 卫星等任务）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/zephyrproject-rtos/zephyr.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Zephyr RTOS` |
| 项目标识 | `zephyr` |
| 项目简介 | Linux 基金会嵌入式实时操作系统，支持多架构、内核可裁剪、驱动生态丰富，星载嵌入式场景广泛使用（如 FINCH 卫星）。镜像收录自 https://github.com/zephyrproject-rtos/zephyr，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 操作系统 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「操作系统」→ 保存

## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
