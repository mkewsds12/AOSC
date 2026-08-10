# NASA OpenMCT

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/openmct
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

OpenMCT 是 NASA 开源的下一代任务控制框架，基于 Web 技术提供可定制的遥测仪表盘、时间线与数据显示组件，已用于多个 NASA 实际任务，可快速搭建任务控制可视化界面。镜像收录自 https://github.com/nasa/openmct，License：Apache-2.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/nasa/openmct.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NASA OpenMCT` |
| 项目标识 | `openmct` |
| 项目简介 | NASA 开源 Web 任务控制框架，可定制遥测仪表盘与数据显示组件，已用于多个实际任务。镜像收录自 https://github.com/nasa/openmct，License：Apache-2.0。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | JavaScript |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE.md，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
