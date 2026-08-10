# Open-Source-Satellite 组织

> 板块：项目管理 / open-source-satellite
> 来源：https://github.com/Open-Source-Satellite
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

早期开源卫星组织主页，包含 Mercury-GS 地面站等项目。内容较少，作为开源卫星早期探索的资料线索收录。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | Open-Source-Satellite 组织-仓库名（每个仓库一个项目） |
| 项目标识 | `open-source-satellite`-仓库名（英文小写） |
| 项目简介 | 早期开源卫星组织主页，包含 Mercury-GS 地面站等项目。内容较少，作为开源卫星早期探索的资料线索收录。镜像收录自 https://github.com/Open-Source-Satellite 组织名下仓库，License：Mercury-GS 为自定义许可（引用 kispe.co.uk 项目许可编号），类型不明 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| Mercury-GS | https://github.com/Open-Source-Satellite/Mercury-GS |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| Open-Source-Satellite/Mercury-GS | ❓ 存在 LICENSE.md（main 分支）但为自定义许可，原文：「All code within this repository is subject to the following license: www.kispe.co.uk/projectlicenses/RA2001001003」 |
- 结论：❓ 许可类型不明（非标准开源许可证），需人工核查该自定义许可条款后再决定
