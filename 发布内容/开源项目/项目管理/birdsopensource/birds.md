# BIRDS 系列

> 板块：项目管理 / BIRDS Open Source（社区镜像）
> 来源：https://github.com/BIRDSOpenSource
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

日本九州工业大学 BIRDS 立方星项目组织主页，BIRDS3/BIRDS4 的 OBC 等分系统软硬件全套开源，曾面向多国推广立方星能力建设。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | BIRDS 系列-仓库名（每个仓库一个项目） |
| 项目标识 | `birds`-仓库名（英文小写） |
| 项目简介 | 日本九州工业大学 BIRDS 立方星项目组织主页，BIRDS3/BIRDS4 的 OBC 等分系统软硬件全套开源，曾面向多国推广立方星能力建设。镜像收录自 https://github.com/BIRDSOpenSource 组织名下仓库，License：MIT（BIRDS3-OBC、BIRDS4-OBC 均为 MIT） |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| BIRDS3-OBC | https://github.com/BIRDSOpenSource/BIRDS3-OBC |
| BIRDS4-OBC | https://github.com/BIRDSOpenSource/BIRDS4-OBC |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| BIRDSOpenSource/BIRDS3-OBC | MIT（LICENSE，main 分支） |
| BIRDSOpenSource/BIRDS4-OBC | MIT（LICENSE，main 分支） |
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
