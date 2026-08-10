# cfs-basecamp

> 板块：项目管理 / cfs-tools
> 来源：https://github.com/cfs-tools/cfs-basecamp
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

cfs-basecamp 是 cfs-tools 组织开源的轻量级 cFS 学习与实验环境，精简了 cFS 部署与配置流程，帮助开发者快速上手星务软件开发、理解软件总线与表/事件服务机制，适合教学培训与原型验证。镜像收录自 https://github.com/cfs-tools/cfs-basecamp，License：GPL-3.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/cfs-tools/cfs-basecamp.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `cfs-basecamp` |
| 项目标识 | `cfs-basecamp` |
| 项目简介 | 轻量级 cFS 学习与实验环境，精简部署配置流程，帮助快速上手星务软件开发，适合教学与原型验证。镜像收录自 https://github.com/cfs-tools/cfs-basecamp，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：GPL-3.0（含作者附加条款，LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规
