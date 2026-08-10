# 美国高校系列（ODU SeaLion）

> 板块：项目管理 / odu-cga-cubesat
> 来源：https://github.com/ODU-CGA-CubeSat
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

美国欧道明大学与海岸警卫队合作的 SeaLion 立方星组织主页，包含 dilophos 飞控 OS、GNU Radio 应用与 Iridium CLI 等仓库。同类高校项目还可参考 ASU-SDSL、CubeSatAtMSU、AlaskaResearchCubeSat/ACDS。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | 美国高校系列（ODU SeaLion）-仓库名（每个仓库一个项目） |
| 项目标识 | `sealion-odu`-仓库名（英文小写） |
| 项目简介 | 美国欧道明大学与海岸警卫队合作的 SeaLion 立方星组织主页，包含 dilophos 飞控 OS、GNU Radio 应用与 Iridium CLI 等仓库。同类高校项目还可参考 ASU-SDSL、CubeSatAtMSU、AlaskaResearchCubeSat/ACDS。镜像收录自 https://github.com/ODU-CGA-CubeSat 组织名下仓库，License：dilophos 为 MIT；gnuradio、iridium-cli 仓库当前无法访问 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| dilophos 飞控 OS | https://github.com/ODU-CGA-CubeSat/dilophos |
| GNU Radio 应用 | https://github.com/ODU-CGA-CubeSat/gnuradio |
| Iridium CLI | https://github.com/ODU-CGA-CubeSat/iridium-cli |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| ODU-CGA-CubeSat/dilophos | MIT（LICENSE，main 分支） |
| ODU-CGA-CubeSat/gnuradio | ❓ 仓库无法访问（404，可能改名/删除/私有） |
| ODU-CGA-CubeSat/iridium-cli | ❓ 仓库无法访问（404，可能改名/删除/私有） |
- 结论：dilophos 许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。其余仓库需人工核查后再决定
