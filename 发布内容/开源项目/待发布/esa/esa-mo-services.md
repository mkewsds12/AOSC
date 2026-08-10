# ESA MO 服务系列

> 板块：项目管理 / ESA（社区镜像）
> 来源：https://github.com/esa/mo-services-java
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

ESA 开源的 CCSDS Mission Operations（MO）服务 Java 实现系列仓库入口，核心为 mo-services-java，配套 mo.viewer.web（Web 可视化）、CCSDS_MO_MAL_IMPL（MAL 抽象层实现）、CCSDS_MO_StubGenerator（桩代码生成）、CCSDS_MO_TRAINING（培训示例），构成完整的 MO 标准开发栈。镜像收录自 https://github.com/esa/mo-services-java，License 以各源仓库 LICENSE 为准。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为系列仓库入口（ESA 组织下多个仓库），需按下方列出的重点仓库逐个导入（每个仓库单独建 GitLink 项目） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | 按各仓库名命名，如 `ESA mo-services-java` |
| 项目标识 | 各仓库英文标识，如 `mo-services-java` |
| 项目简介 | 按各仓库说明填写，末尾含「镜像收录自 https://github.com/esa/{仓库名}，License 以源仓库 LICENSE 为准」 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | Java |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| mo-services-java（MO 服务 Java 实现） | https://github.com/esa/mo-services-java |
| mo.viewer.web（Web 可视化） | https://github.com/esa/mo.viewer.web |
| CCSDS_MO_MAL_IMPL | https://github.com/esa/CCSDS_MO_MAL_IMPL |
| CCSDS_MO_StubGenerator | https://github.com/esa/CCSDS_MO_StubGenerator |
| CCSDS_MO_TRAINING | https://github.com/esa/CCSDS_MO_TRAINING |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）

| 仓库 | 许可证 | LICENSE 文件 / 分支 | 结论 |
|------|--------|--------------------|------|
| esa/CCSDS_MO_MAL_IMPL | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| esa/CCSDS_MO_StubGenerator | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| esa/CCSDS_MO_TRAINING | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| esa/mo-services-java | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| esa/mo.viewer.web | MIT | LICENSE.txt / master | 可镜像；保留 LICENSE 与版权声明 |

- 结论：仅 mo.viewer.web 许可证明确可镜像；其余 4 个仓库未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支），**不可镜像代码**，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
