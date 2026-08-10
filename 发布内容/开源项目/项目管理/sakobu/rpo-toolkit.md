# rpo-toolkit（交会对接）

> 板块：项目管理 / sakobu
> 来源：https://github.com/sakobu/rpo-toolkit
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

rpo-toolkit 是航天器交会对接近距操作（RPO）规划工具箱，基于 Rust 实现，提供近距相对运动建模与轨迹规划能力，适用于在轨服务与交会对接任务的制导算法研究。另可参考 orbital-rl（CW 方程 PPO 强化学习）。镜像收录自 https://github.com/sakobu/rpo-toolkit ，License：AGPL-3.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/sakobu/rpo-toolkit.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `rpo-toolkit（交会对接）` |
| 项目标识 | `rpo-toolkit` |
| 项目简介 | 航天器交会对接近距操作（RPO）规划工具箱，Rust 实现，提供近距相对运动建模与轨迹规划能力，适用于在轨服务与交会对接制导研究；另可参考 orbital-rl。镜像收录自 https://github.com/sakobu/rpo-toolkit ，License：AGPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 姿控算法 |
| 项目语言 | Rust |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「姿控算法」→ 保存

## 许可证核查（2026-08-10）
- 结果：AGPL-3.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
- 义务提醒：AGPL-3.0：衍生/分发需开源同等授权，且通过网络提供服务也触发源码开放义务；镜像只读展示合规
