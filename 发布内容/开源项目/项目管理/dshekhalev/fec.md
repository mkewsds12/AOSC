# FEC 编码库

> 板块：项目管理 / dshekhalev
> 来源：https://github.com/dshekhalev/FEC
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

本项目是 BCH/RS/LDPC/Turbo 等前向纠错（FEC）码的 SystemVerilog IP 核集合，面向 FPGA 实现，可直接集成到卫星通信基带设计中，是星载与地面站基带硬件开发的实用参考。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/dshekhalev/FEC.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `FEC 编码库` |
| 项目标识 | `fec` |
| 项目简介 | BCH/RS/LDPC/Turbo 前向纠错码 SystemVerilog IP 核集合，面向 FPGA 实现，可集成到卫星通信基带设计，是星载与地面站基带硬件开发的实用参考。镜像收录自 https://github.com/dshekhalev/FEC，License：MIT |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | SystemVerilog |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
