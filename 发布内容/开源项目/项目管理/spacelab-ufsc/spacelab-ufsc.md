# spacelab-ufsc

> 板块：项目管理 / spacelab-ufsc
> 来源：https://github.com/spacelab-ufsc
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

spacelab-ufsc 是巴西 UFSC 太空实验室的开源组织主页，开源了 obdh2（星载数据计算机）、eps2（电源分系统）、ttc2（测控分系统）等全套立方星分系统软硬件项目，覆盖星务处理核心环节，工程文档与代码质量较高。镜像收录自 https://github.com/spacelab-ufsc，License 以各源仓库 LICENSE 为准。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库单独建 GitLink 项目） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | 按各仓库名命名，如 `spacelab-ufsc obdh2` |
| 项目标识 | 各仓库英文标识，如 `obdh2`、`eps2`、`ttc2` |
| 项目简介 | 按各仓库说明填写，末尾含「镜像收录自 https://github.com/spacelab-ufsc，License 以源仓库 LICENSE 为准」 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | 以源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| obdh2（星载数据计算机） | https://github.com/spacelab-ufsc/obdh2 |
| eps2（电源分系统） | https://github.com/spacelab-ufsc/eps2 |
| ttc2（测控分系统） | https://github.com/spacelab-ufsc/ttc2 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）

| 仓库 | 许可证 | LICENSE 文件 / 分支 | 结论 |
|------|--------|--------------------|------|
| spacelab-ufsc/eps2 | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| spacelab-ufsc/obdh2 | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| spacelab-ufsc/ttc2 | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |

- 结论：3 个重点仓库均未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支），**不可镜像代码**，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
