# NASA cFS

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/cFS
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

NASA 核心飞行系统（core Flight System，cFS）官方捆绑仓库，集成 cFE 核心执行环境、官方应用与开发工具，可一键搭建完整的开源飞行软件基线，适合星务软件开发、教学与原型验证。镜像收录自 https://github.com/nasa/cFS，License：Apache-2.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/nasa/cFS.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NASA cFS` |
| 项目标识 | `cfs` |
| 项目简介 | NASA 核心飞行系统官方捆绑仓库（cFE + 应用 + 工具），可快速搭建完整开源飞行软件基线。镜像收录自 https://github.com/nasa/cFS，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
