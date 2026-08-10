# ESA GitLab 组织

> 板块：项目管理 / ESA（社区镜像）
> 来源：https://gitlab.com/EuropeanSpaceAgency
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

ESA（欧洲航天局）官方 GitLab 组织入口，集中托管 ESA 官方开源项目，包括 OPS-SAT 竞赛入门套件等在轨实验与星上软件相关仓库，是获取 ESA 官方航天开源软件的主要入口。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `ESA GitLab 组织` |
| 项目标识 | `esa-gitlab` |
| 项目简介 | ESA 官方 GitLab 组织入口，集中托管 ESA 官方开源项目（OPS-SAT 竞赛套件等），是获取 ESA 官方航天开源软件的主要入口。来源 https://gitlab.com/EuropeanSpaceAgency，License 见文末许可证核查表 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步；对重点仓库逐个勾选） |
| 项目类别 | 算法处理 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「算法处理」→ 保存

## 组织内重点仓库（逐个导入，仓库名以实际为准）

| 仓库名 | URL |
|--------|-----|
| the_opssat_case_starter_kit（OPS-SAT 竞赛入门套件，已单独收录） | https://gitlab.com/EuropeanSpaceAgency/the_opssat_case_starter_kit |

> 其余仓库清单以组织主页 https://gitlab.com/EuropeanSpaceAgency 实际为准，导入前人工确认。

## 许可证核查（2026-08-10）
组织主页类条目，对文末列出的重点仓库逐一核查（GitLab raw 探测 LICENSE/LICENSE.md/LICENSE.txt/COPYING/COPYRIGHT，main/master 分支）：

| 仓库 | 结果 |
| --- | --- |
| EuropeanSpaceAgency/the_opssat_case_starter_kit | ⚠️ 未检测到 LICENSE 文件（仓库可访问，main 分支） |

- 结论：组织入口本身可收录链接；重点仓库**不可镜像代码**，建议只收录官方链接；如确需镜像，先联系 ESA 项目维护者获得许可
