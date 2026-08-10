# nmf-mission-ops-sat

> 板块：项目管理 / ESA（社区镜像）
> 来源：https://github.com/esa/nmf-mission-ops-sat
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

nmf-mission-ops-sat 是运行在 ESA OPS-SAT 卫星上的 NanoSat MO Framework（NMF）任务适配层，基于 CCSDS MO 标准实现星上软件服务的封装与调度，使地面标准服务接口可直接用于在轨应用，是星上服务化软件架构的重要参考。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/esa/nmf-mission-ops-sat.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `nmf-mission-ops-sat` |
| 项目标识 | `nmf-mission-ops-sat` |
| 项目简介 | OPS-SAT 上的 NanoSat MO Framework 任务适配层，基于 CCSDS MO 标准实现星上软件服务封装与调度。镜像收录自 https://github.com/esa/nmf-mission-ops-sat，未检测到 LICENSE 文件 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 算法处理 |
| 项目语言 | Java |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「算法处理」→ 保存

## 许可证核查（2026-08-10）
- 结果：⚠️ 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支）
- 结论：**不可镜像代码**。公开仓库不等于授权，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
