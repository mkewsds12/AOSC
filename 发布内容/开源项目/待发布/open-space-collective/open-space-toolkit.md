# open-space-toolkit

> 板块：项目管理 / open-space-collective
> 来源：https://github.com/open-space-collective
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

open-space-toolkit 是 Open Space Collective 组织维护的开源太空工具包（C++ 核心，Python 绑定），覆盖飞行动力学、轨道、姿态与访问计算等能力，工程化程度高，可直接用于地面软件与任务分析。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库单独执行一次「导入项目」，项目标识用仓库英文名） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `open-space-toolkit`（按各仓库实际名称分别命名） |
| 项目标识 | `open-space-toolkit`（按各仓库英文名分别填写） |
| 项目简介 | open-space-toolkit 是 Open Space Collective 组织维护的开源太空工具包（C++ 核心，Python 绑定），覆盖飞行动力学、轨道、姿态与访问计算等能力，工程化程度高，可直接用于地面软件与任务分析。镜像收录自 https://github.com/open-space-collective，License：Apache-2.0（各仓库均为 Apache-2.0，详见文末核查） |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 轨道仿真 |
| 项目语言 | C++ |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL（导入时末尾加 .git） |
|------|--------------------------|
| `open-space-toolkit-core` | https://github.com/open-space-collective/open-space-toolkit-core |
| `open-space-toolkit-io` | https://github.com/open-space-collective/open-space-toolkit-io |
| `open-space-toolkit-mathematics` | https://github.com/open-space-collective/open-space-toolkit-mathematics |
| `open-space-toolkit-physics` | https://github.com/open-space-collective/open-space-toolkit-physics |
| `open-space-toolkit-astrodynamics` | https://github.com/open-space-collective/open-space-toolkit-astrodynamics |
| `open-space-toolkit-flight` | https://github.com/open-space-collective/open-space-toolkit-flight |
| `open-space-toolkit-simulation` | https://github.com/open-space-collective/open-space-toolkit-simulation |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「轨道仿真」→ 保存

## 许可证核查（2026-08-10）
- 结果：组织主页来源，对重点仓库逐个核查：

| 仓库 | 许可证 | 说明 |
|------|--------|------|
| open-space-toolkit-core | Apache-2.0 | LICENSE，main 分支 |
| open-space-toolkit-io | Apache-2.0 | LICENSE，main 分支 |
| open-space-toolkit-mathematics | Apache-2.0 | LICENSE，main 分支 |
| open-space-toolkit-physics | Apache-2.0 | LICENSE，main 分支 |
| open-space-toolkit-astrodynamics | Apache-2.0 | LICENSE，main 分支 |
| open-space-toolkit-simulation | Apache-2.0 | LICENSE，main 分支 |
| open-space-toolkit-flight | ❓ 仓库无法访问（404，可能已删除/改名/归档） | 组织现有仓库中含 open-space-toolkit-data，建议人工确认后替换 |

- 结论：除 flight 外许可证明确（Apache-2.0），可镜像；镜像时保留各仓库 LICENSE 与版权声明。flight 需人工核查后再决定是否导入
