# KENSAT

> 板块：项目管理 / kenchangh
> 来源：https://github.com/kenchangh/kensat
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

KENSAT 是一颗 2U 立方星，在轨运行大语言模型，搭载 Jetson Orin Nano 边缘计算平台，实现星上大模型推理。该项目是星上智能（AI in Space）的代表性实践，展示了边缘 GPU 在微小卫星上运行 LLM 的可行性。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/kenchangh/kensat.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `KENSAT` |
| 项目标识 | `kensat` |
| 项目简介 | 2U 立方星在轨运行大语言模型（Jetson Orin Nano），星上智能代表项目，验证边缘 GPU 星上运行 LLM 的可行性。镜像收录自 https://github.com/kenchangh/kensat，License：MIT |
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
