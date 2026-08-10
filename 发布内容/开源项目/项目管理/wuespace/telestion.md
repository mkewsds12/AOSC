# Telestion

> 板块：项目管理 / wuespace
> 来源：https://github.com/wuespace/telestion
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Telestion 是德国 WüSpace 团队开源的任务控制与地面站框架，采用模块化微服务架构与 Web 前端，支持遥测监控、指令发送与自定义扩展，面向学生团队与小型卫星任务。镜像收录自 https://github.com/wuespace/telestion，License：MIT。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/wuespace/telestion.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Telestion` |
| 项目标识 | `telestion` |
| 项目简介 | 德国 WüSpace 开源任务控制/地面站框架，模块化微服务架构 + Web 前端，支持遥测监控与指令发送。镜像收录自 https://github.com/wuespace/telestion，License：MIT。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
