# gncpy

> 板块：项目管理 / drjdlarson
> 来源：https://github.com/drjdlarson/gncpy
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

gncpy 是阿拉巴马大学开源的 GNC（导航、制导与控制）算法库，基于 Python 实现，包含卡尔曼滤波、非线性估计、最优控制等常用算法，适合航天器 GNC 算法研究与快速原型验证。镜像收录自 https://github.com/drjdlarson/gncpy ，License：MIT。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/drjdlarson/gncpy.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `gncpy` |
| 项目标识 | `gncpy` |
| 项目简介 | 阿拉巴马大学开源 GNC 算法库，Python 实现，涵盖卡尔曼滤波、非线性估计、最优控制等导航/制导/控制算法，适合航天器 GNC 研究与快速原型验证。镜像收录自 https://github.com/drjdlarson/gncpy ，License：MIT |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 姿控算法 |
| 项目语言 | Python |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「姿控算法」→ 保存

## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
