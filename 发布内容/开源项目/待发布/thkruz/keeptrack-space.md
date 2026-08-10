# keeptrack.space

> 板块：项目管理 / thkruz
> 来源：https://github.com/thkruz/keeptrack.space
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

keeptrack.space 是一个开源的卫星 3D 跟踪与可视化项目，基于 Web 技术实现在轨目标的实时三维展示、轨道分析与编目查询，界面直观，适合空间态势感知与教学演示。镜像收录自 https://github.com/thkruz/keeptrack.space，License：AGPL-3.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/thkruz/keeptrack.space.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `keeptrack.space` |
| 项目标识 | `keeptrack-space` |
| 项目简介 | 开源卫星 3D 跟踪可视化项目，Web 端实时展示在轨目标、轨道分析与编目查询。镜像收录自 https://github.com/thkruz/keeptrack.space，License：AGPL-3.0。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | TypeScript |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：AGPL-3.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。AGPL-3.0：衍生/分发及通过网络提供服务均需开源同等授权；镜像只读展示合规
