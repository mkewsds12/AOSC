# sat-rs

> 备注：该项目可能已按本流程导入过 sds3 组织，若已完成镜像导入则跳过导入步骤，直接执行上架。

> 板块：项目管理 / IRS Stuttgart
> 来源：https://github.com/us-irs/sat-rs
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

sat-rs 是德国斯图加特大学 IRS 团队开源的 Rust 星载软件库，实现 ECSS PUS、CCSDS 空间包等标准原语，类型安全、内存安全，适合以 Rust 构建高可靠星务与星载应用软件。镜像收录自 https://github.com/us-irs/sat-rs，License：Apache-2.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/us-irs/sat-rs.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `sat-rs` |
| 项目标识 | `sat-rs` |
| 项目简介 | 德国 IRS 开源的 Rust 星载软件库，实现 ECSS PUS 与 CCSDS 标准原语，适合构建高可靠星务软件。镜像收录自 https://github.com/us-irs/sat-rs，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | Rust |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE-APACHE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
