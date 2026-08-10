# r2cloud

> 板块：项目管理 / dernasherbrezon
> 来源：https://github.com/dernasherbrezon/r2cloud
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

r2cloud 是面向树莓派的自动卫星信号解码与调度系统，可驱动 SDR 按预报自动接收、解码多颗卫星信号并管理观测数据，实现无人值守的低成本自动化地面站。镜像收录自 https://github.com/dernasherbrezon/r2cloud，License：Apache-2.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/dernasherbrezon/r2cloud.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `r2cloud` |
| 项目标识 | `r2cloud` |
| 项目简介 | 树莓派自动卫星信号解码与调度系统，SDR 自动接收解码、无人值守，构建低成本自动化地面站。镜像收录自 https://github.com/dernasherbrezon/r2cloud，License：Apache-2.0。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | Java |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
