# ecss-services

> 板块：项目管理 / AcubeSAT（社区镜像）
> 来源：https://github.com/AcubeSAT/ecss-services
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

ecss-services 是希腊 AcubeSAT 纳米卫星团队开源的 ECSS PUS 服务 C++ 实现，覆盖参数、事件、存储管理、调度等标准星务服务，模块化设计且活跃维护，可直接用于星载软件或作为 PUS 标准实现参考。镜像收录自 https://github.com/AcubeSAT/ecss-services，License：MIT。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/AcubeSAT/ecss-services.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `ecss-services` |
| 项目标识 | `ecss-services` |
| 项目简介 | AcubeSAT 纳米星团队开源的 ECSS PUS 服务 C++ 实现，模块化设计、活跃维护，可直接用于星载软件。镜像收录自 https://github.com/AcubeSAT/ecss-services，License：MIT |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | C++ |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
