# edge-ai-satellite-triage

> 板块：项目管理 / interactiveintel
> 来源：https://github.com/interactiveintel/edge-ai-satellite-triage
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

edge-ai-satellite-triage 实现星上数据智能分流：结合 CNN 分类、ReAct 智能体决策与审计机制，在 Jetson Orin 边缘平台上完成在轨数据的筛选与优先下传决策，提升星地链路利用率。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/interactiveintel/edge-ai-satellite-triage.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `edge-ai-satellite-triage` |
| 项目标识 | `edge-ai-satellite-triage` |
| 项目简介 | 星上数据分流系统：CNN + ReAct 智能体 + 审计机制，运行于 Jetson Orin，完成在轨数据筛选与优先下传决策。镜像收录自 https://github.com/interactiveintel/edge-ai-satellite-triage，License：MIT |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 算法处理 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「算法处理」→ 保存

## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
