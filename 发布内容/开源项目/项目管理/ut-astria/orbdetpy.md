# OrbDetPy

> 板块：项目管理 / ut-astria
> 来源：https://github.com/ut-astria/orbdetpy
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

OrbDetPy 是德克萨斯大学奥斯汀分校 ASTRIA 团队开发的轨道确定库，结合 Orekit 与卡尔曼滤波，支持利用测距、角度等观测数据进行卫星轨道确定与批量最小二乘解算。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/ut-astria/orbdetpy.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `OrbDetPy` |
| 项目标识 | `orbdetpy` |
| 项目简介 | OrbDetPy 是德克萨斯大学奥斯汀分校 ASTRIA 团队开发的轨道确定库，结合 Orekit 与卡尔曼滤波，支持利用测距、角度等观测数据进行卫星轨道确定与批量最小二乘解算。镜像收录自 https://github.com/ut-astria/orbdetpy，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 轨道仿真 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「轨道仿真」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规
