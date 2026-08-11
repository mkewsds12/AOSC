# Outfit

> 板块：项目管理 / fusroman
> 来源：https://github.com/FusRoman/Outfit
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Outfit 是 Rust 编写的小天体定轨与传播库，支持 MPC 观测格式、Gauss 初轨确定方法与 JPL 行星历表，面向小行星观测数据处理。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/FusRoman/Outfit.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Outfit` |
| 项目标识 | `outfit` |
| 项目简介 | Outfit 是 Rust 编写的小天体定轨与传播库，支持 MPC 观测格式、Gauss 初轨确定方法与 JPL 行星历表，面向小行星观测数据处理。镜像收录自 https://github.com/FusRoman/Outfit，License：CeCILL-C |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 轨道仿真 |
| 项目语言 | Rust |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「轨道仿真」→ 保存

## 许可证核查（2026-08-10）
- 结果：CeCILL-C（LICENSE，main 分支；法国弱 copyleft 许可，与 LGPL 兼容）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。CeCILL-C：衍生分发需同等授权且受法国法律管辖；镜像只读展示合规
