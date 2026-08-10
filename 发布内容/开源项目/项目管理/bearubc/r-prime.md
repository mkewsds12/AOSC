# r-prime

> 板块：项目管理 / BEARUBC
> 来源：https://github.com/BEARUBC/r-prime
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

r-prime 是加拿大 UBC 团队用 Rust 实现的轻量级类 F' 飞行软件框架，借鉴 F Prime 的组件化设计，利用 Rust 的内存安全特性，为小型卫星星务软件提供更轻量、更安全的实现选择。镜像收录自 https://github.com/BEARUBC/r-prime，License：MIT。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/BEARUBC/r-prime.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `r-prime` |
| 项目标识 | `r-prime` |
| 项目简介 | Rust 实现的轻量级类 F' 飞行软件框架，组件化设计 + 内存安全，面向小型卫星星务软件。镜像收录自 https://github.com/BEARUBC/r-prime，License：MIT |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | Rust |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE.md，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
