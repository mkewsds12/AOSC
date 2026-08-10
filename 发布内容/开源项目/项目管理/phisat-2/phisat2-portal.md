# PhiSat-2 Portal

> 板块：项目管理 / PhiSat-2
> 来源：https://github.com/PhiSat-2
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

PhiSat-2 官方组织主页，集中维护 PhiSat-2 任务相关的官方数据访问指南与数据集格式规范等仓库，是获取 PhiSat-2 在轨 AI 实验数据与接入文档的生态入口。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `PhiSat-2 Portal` |
| 项目标识 | `phisat2-portal` |
| 项目简介 | PhiSat-2 官方组织入口，集中维护任务数据访问指南与数据集格式规范等仓库，是获取 PhiSat-2 在轨 AI 实验数据的生态入口。来源 https://github.com/PhiSat-2，License 见文末许可证核查表 |
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
| data-access-guide（数据访问指南） | https://github.com/PhiSat-2/data-access-guide |
| dataset-format（数据集格式规范） | https://github.com/PhiSat-2/dataset-format |

> 以上仓库名为推测，实际仓库名与清单以组织主页 https://github.com/PhiSat-2 为准。

## 许可证核查（2026-08-10）
组织主页类条目，对文末列出的重点仓库逐一核查（GitHub raw 探测 LICENSE 系列文件及 README，main/master 分支）：

| 仓库 | 结果 |
| --- | --- |
| PhiSat-2/data-access-guide | ❓ 仓库无法访问（404，可能改名/删除/私有；文件中也注明仓库名为推测） |
| PhiSat-2/dataset-format | ❓ 仓库无法访问（404，可能改名/删除/私有；文件中也注明仓库名为推测） |

- 结论：需人工核查后再决定。建议先在组织主页 https://github.com/PhiSat-2 核实实际仓库清单，再对各仓库做许可证核查；核查通过前不可镜像
