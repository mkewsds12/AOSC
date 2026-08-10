# rio-tiler

> 板块：项目管理 / cogeotiff
> 来源：https://github.com/cogeotiff/rio-tiler
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

rio-tiler 是基于 rasterio 的 COG（Cloud Optimized GeoTIFF）遥感影像瓦片服务库，可按 XYZ 瓦片规范从云端优化的 GeoTIFF 中高效读取并生成地图瓦片。轻量易集成，常与 FastAPI 等框架搭配搭建动态瓦片服务，是遥感影像在线发布的基础设施。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/cogeotiff/rio-tiler.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `rio-tiler` |
| 项目标识 | `rio-tiler` |
| 项目简介 | 基于 rasterio 的 COG 遥感影像瓦片服务库，按 XYZ 规范从云端优化 GeoTIFF 高效生成地图瓦片，常与 FastAPI 搭配搭建动态瓦片服务。镜像收录自 https://github.com/cogeotiff/rio-tiler，License：BSD-3-Clause |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 应用服务 |
| 项目语言 | Python |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「应用服务」→ 保存

## 许可证核查（2026-08-10）
- 结果：BSD-3-Clause（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
