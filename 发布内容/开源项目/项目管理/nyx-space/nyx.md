# Nyx

> 板块：项目管理 / nyx-space（社区镜像）
> 来源：https://gitlab.com/chrisrabotin/nyx
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Nyx 是 Rust 编写的高保真天体动力学与轨道确定工具包，支持高精度轨道传播、轨道确定（含卡尔曼滤波）与任务分析，性能出色，已用于实际任务分析场景。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://gitlab.com/chrisrabotin/nyx.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Nyx` |
| 项目标识 | `nyx` |
| 项目简介 | Nyx 是 Rust 编写的高保真天体动力学与轨道确定工具包，支持高精度轨道传播、轨道确定（含卡尔曼滤波）与任务分析，性能出色，已用于实际任务分析场景。镜像收录自 https://gitlab.com/chrisrabotin/nyx，License：AGPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 轨道仿真 |
| 项目语言 | Rust |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「轨道仿真」→ 保存

## 许可证核查（2026-08-10）
- 结果：AGPL-3.0（LICENSE，master 分支；原地址 gitlab.com/chrisrabotin/nyx 已 301 重定向至 gitlab.com/nyx-space/nyx）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。AGPL-3.0：衍生/分发及网络服务使用均需开源同等授权；镜像只读展示合规。导入 URL 建议改用新地址 https://gitlab.com/nyx-space/nyx
