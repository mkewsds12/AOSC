# Space Grade Linux

> 板块：项目管理 / containers
> 来源：https://github.com/containers/space-grade-linux
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Space Grade Linux 是面向航天场景的 Linux 发行版，提供 SELinux 安全加固、实时内核以及基于 Podman 的容器化运行环境，用于构建高可靠星载 Linux 系统。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/containers/space-grade-linux.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Space Grade Linux` |
| 项目标识 | `space-grade-linux` |
| 项目简介 | 面向航天场景的 Linux 发行版：SELinux 安全加固、实时内核、基于 Podman 的容器化运行环境，用于构建高可靠星载 Linux 系统。镜像收录自 https://github.com/containers/space-grade-linux，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 操作系统 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「操作系统」→ 保存

## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
