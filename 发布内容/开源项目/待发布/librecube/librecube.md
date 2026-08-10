# LibreCube

> 板块：项目管理 / librecube
> 来源：https://gitlab.com/librecube
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

开源太空探索组件生态组织主页，提供结构、电源、星载计算机、EGSE 等全套开源组件，目标是让人人都能构建自己的航天器。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | LibreCube-仓库名（每个仓库一个项目） |
| 项目标识 | `librecube`-仓库名（英文小写） |
| 项目简介 | 开源太空探索组件生态组织主页，提供结构、电源、星载计算机、EGSE 等全套开源组件，目标是让人人都能构建自己的航天器。镜像收录自 https://gitlab.com/librecube 组织名下仓库，License：4 个重点仓库当前均无法访问（组织已重组），详见文末核查节 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| 结构组件 | https://gitlab.com/librecube/structure |
| 电源组件 | https://gitlab.com/librecube/power |
| 星载计算机 | https://gitlab.com/librecube/computer |
| EGSE | https://gitlab.com/librecube/egse |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| librecube/computer | ❓ 仓库无法访问（组织已重组为 components/LCxxxx 结构，路径不存在） |
| librecube/egse | ❓ 仓库无法访问（同上） |
| librecube/power | ❓ 仓库无法访问（同上） |
| librecube/structure | ❓ 仓库无法访问（同上） |
- 结论：❓ 仓库无法访问（组织已重组，原路径删除/改名），需人工核对 librecube/components 下实际仓库及其许可证后再决定
