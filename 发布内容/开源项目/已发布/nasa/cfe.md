# NASA cFE

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/cFE
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

NASA 核心飞行执行环境（core Flight Executive，cFE），是 cFS 飞行软件体系的核心运行时，提供软件总线、表服务、事件服务、文件服务等基础能力，广泛运行于 NASA 多型号任务，是国际开源星务软件的事实标准之一。镜像收录自 https://github.com/nasa/cFE，License：Apache-2.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/nasa/cFE.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NASA cFE` |
| 项目标识 | `cfe` |
| 项目简介 | NASA cFS 体系的核心执行环境，提供软件总线、表、事件、文件等基础服务，是开源星务软件事实标准。镜像收录自 https://github.com/nasa/cFE，License：Apache-2.0 |
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
