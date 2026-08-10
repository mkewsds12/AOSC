# NASA AMMOS 系列

> 板块：项目管理 / NASA AMMOS（社区镜像）
> 来源：https://github.com/NASA-AMMOS
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

NASA AMMOS（Advanced Multi-Mission Operations System）是 NASA JPL 的多任务地面系统开源组织，包含 AIT-Core（地面数据系统/EGSE）、AIT-GUI、AIT-CFS、AIT-DSN、MMTC（任务对时）、MMGIS（地表可视化）等组件，覆盖地面测控全链路。镜像收录自 https://github.com/NASA-AMMOS，License：各仓库分别核查，见文末「许可证核查」节。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NASA AMMOS 系列` |
| 项目标识 | `nasa-ammos` |
| 项目简介 | NASA JPL 多任务地面系统系列：AIT-Core（GDS/EGSE）、AIT-GUI、AIT-CFS、AIT-DSN、MMTC 对时、MMGIS 等。镜像收录自 https://github.com/NASA-AMMOS，License：各仓库分别核查，见文末「许可证核查」节。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 重点仓库（逐个镜像导入）

| 仓库名 | URL |
|--------|-----|
| AIT-Core | https://github.com/NASA-AMMOS/AIT-Core |
| AIT-GUI | https://github.com/NASA-AMMOS/AIT-GUI |
| AIT-CFS | https://github.com/NASA-AMMOS/AIT-CFS |
| AIT-DSN | https://github.com/NASA-AMMOS/AIT-DSN |
| MMTC | https://github.com/NASA-AMMOS/MMTC |
| MMGIS | https://github.com/NASA-AMMOS/MMGIS |
| landscape | https://github.com/NASA-AMMOS/landscape |

（仓库名以实际为准）

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果（组织主页逐仓库核查）：

| 仓库 | 许可证 | LICENSE 文件/分支 | 结论 |
|------|--------|------------------|------|
| AIT-Core | MIT | LICENSE.txt，master | 可镜像 |
| AIT-GUI | ❓ 仓库无法访问（README 在 main/master 均 404，可能改名/删除/私有） | — | 需人工核查后再决定 |
| AIT-CFS | MIT | LICENSE.txt，master | 可镜像 |
| AIT-DSN | MIT | LICENSE.txt，master | 可镜像 |
| MMTC | Apache-2.0 | LICENSE.md，main | 可镜像 |
| MMGIS | Apache-2.0 | LICENSE，master | 可镜像 |
| landscape | Apache-2.0 | LICENSE，main | 可镜像 |

- 结论：除 AIT-GUI 外各仓库许可证明确，可镜像；镜像时保留各仓库 LICENSE 与版权声明。AIT-GUI 需人工确认仓库状态后再决定
