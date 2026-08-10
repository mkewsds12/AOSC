# Virtual Satellite

> 板块：项目管理 / virtualsatellite
> 来源：https://github.com/virtualsatellite/VirtualSatellite4-Core
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Virtual Satellite 是德国宇航中心（DLR）开源的星上系统建模与仿真框架，基于模型化系统工程（MBSE）方法支持航天器系统设计、数据管理与任务各阶段的协同建模。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/virtualsatellite/VirtualSatellite4-Core.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Virtual Satellite` |
| 项目标识 | `virtualsatellite` |
| 项目简介 | Virtual Satellite 是德国宇航中心（DLR）开源的星上系统建模与仿真框架，基于模型化系统工程（MBSE）方法支持航天器系统设计、数据管理与任务各阶段的协同建模。镜像收录自 https://github.com/virtualsatellite/VirtualSatellite4-Core，License：EPL-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 轨道仿真 |
| 项目语言 | Java |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「轨道仿真」→ 保存

## 许可证核查（2026-08-10）
- 结果：EPL-2.0（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
