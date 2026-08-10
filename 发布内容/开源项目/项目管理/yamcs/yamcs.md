# Yamcs

> 板块：项目管理 / Yamcs
> 来源：https://github.com/yamcs/yamcs
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Yamcs 是基于 Java 的开源任务控制框架（MCS），支持 CCSDS/ECSS 标准，提供遥测处理归档、指令发送、参数显示与自动化脚本能力，被 ESA 及多家商业航天公司广泛用于地面测控系统。镜像收录自 https://github.com/yamcs/yamcs，License：未检测到 LICENSE 文件。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/yamcs/yamcs.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Yamcs` |
| 项目标识 | `yamcs` |
| 项目简介 | Java 开源任务控制框架，支持 CCSDS/ECSS，含遥测处理、指令发送与自动化，ESA 与商业航天广泛使用。镜像收录自 https://github.com/yamcs/yamcs，License：未检测到 LICENSE 文件。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | Java |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：⚠️ 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支）
- 结论：**不可镜像代码**。公开仓库不等于授权，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
