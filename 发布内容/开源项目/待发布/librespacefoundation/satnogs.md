# SatNOGS

> 板块：项目管理 / Libre Space Foundation
> 来源：https://gitlab.com/librespacefoundation/satnogs
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

SatNOGS 是全球众包开源地面站网络，由 Libre Space Foundation 维护，包含地面站客户端（client）、观测数据库（db）、自动调度（auto-scheduler）、解码器（decoders）等全套组件，任何人都可以搭建自己的地面站并接入全球网络共享观测数据。镜像收录自 https://gitlab.com/librespacefoundation/satnogs，License：各仓库分别核查，见文末「许可证核查」节。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `SatNOGS` |
| 项目标识 | `satnogs` |
| 项目简介 | 全球众包开源地面站网络，含客户端、数据库、自动调度与解码器全套组件，可自建地面站接入全球观测网络。镜像收录自 https://gitlab.com/librespacefoundation/satnogs，License：各仓库分别核查，见文末「许可证核查」节。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 重点仓库（逐个镜像导入）

| 仓库名 | URL |
|--------|-----|
| satnogs-client | https://gitlab.com/librespacefoundation/satnogs/satnogs-client |
| satnogs-db | https://gitlab.com/librespacefoundation/satnogs/satnogs-db |
| satnogs-auto-scheduler | https://gitlab.com/librespacefoundation/satnogs/satnogs-auto-scheduler |
| satnogs-decoders | https://gitlab.com/librespacefoundation/satnogs/satnogs-decoders |

（仓库名以实际为准）

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果（组织主页逐仓库核查）：

| 仓库 | 许可证 | LICENSE 文件/分支 | 结论 |
|------|--------|------------------|------|
| satnogs-client | AGPL-3.0 | LICENSE，master | 可镜像 |
| satnogs-db | AGPL-3.0 | LICENSE，master | 可镜像 |
| satnogs-auto-scheduler | AGPL-3.0 | LICENSE，master | 可镜像 |
| satnogs-decoders | AGPL-3.0 | LICENSE，master | 可镜像 |

- 结论：各仓库许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。AGPL-3.0：衍生/分发及通过网络提供服务均需开源同等授权；镜像只读展示合规
