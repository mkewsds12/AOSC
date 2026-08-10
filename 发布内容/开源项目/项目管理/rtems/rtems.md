# RTEMS

> 板块：项目管理 / rtems
> 来源：https://gitlab.rtems.org/rtems/rtos/rtems
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

RTEMS（Real-Time Executive for Multiprocessor Systems）是经典的航天实时操作系统，被 NASA、ESA 等机构长期使用，支持多种处理器架构，具有成熟的硬实时调度与航天任务验证历史。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://gitlab.rtems.org/rtems/rtos/rtems.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `RTEMS` |
| 项目标识 | `rtems` |
| 项目简介 | 经典航天实时操作系统，NASA/ESA 长期任务使用，支持多处理器架构与硬实时调度，拥有大量在轨飞行验证历史。镜像收录自 https://gitlab.rtems.org/rtems/rtos/rtems，License：无法自动确认，见文末许可证核查节 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 操作系统 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「操作系统」→ 保存

## 许可证核查（2026-08-10）
- 结果：❓ 网络探测失败——gitlab.rtems.org 触发反爬限流（HTTP 429），候选许可证文件均无法稳定取回
- 结论：需人工核查后再决定（可人工访问源仓库页面确认 LICENSE 条款）
