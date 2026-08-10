# KCSA 开源卫星组织

> 板块：项目管理 / opensatellite
> 来源：https://gitee.com/opensatellite
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

中国开源卫星组织（KCSA）Gitee 主页，包含 KS-1Q 开源立方星与 gr-kcsa-ks1q 测控 GNU Radio 模块等项目，是国产开源卫星的核心阵地。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | KCSA 开源卫星组织-仓库名（每个仓库一个项目） |
| 项目标识 | `kcsa-opensatellite`-仓库名（英文小写） |
| 项目简介 | 中国开源卫星组织（KCSA）Gitee 主页，包含 KS-1Q 开源立方星与 gr-kcsa-ks1q 测控 GNU Radio 模块等项目，是国产开源卫星的核心阵地。镜像收录自 https://gitee.com/opensatellite 组织名下仓库，License：KS-1Q 为 LGPL-2.1；gr-kcsa-ks1q 仓库当前无法访问 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| KS-1Q | https://gitee.com/opensatellite/KS-1Q |
| gr-kcsa-ks1q | https://gitee.com/opensatellite/gr-kcsa-ks1q |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| opensatellite/KS-1Q | LGPL-2.1（LICENSE，master 分支） |
| opensatellite/gr-kcsa-ks1q | ❓ 仓库无法访问（404，可能改名/删除/私有） |
- 结论：KS-1Q 许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。LGPL-2.1：修改/衍生部分需以 LGPL 开源；镜像只读展示合规。gr-kcsa-ks1q 需人工核查后再决定
