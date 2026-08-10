# PyCubed-Mini

> 板块：项目管理 / pycubed-mini
> 来源：https://github.com/PyCubed-Mini
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

PyCubed 的 PocketQube 版本组织主页，开源 avionics-mainboard 主控板与 avionics-batteryboard 电池板，延续 PyCubed 的开源 OBC 标杆路线。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | PyCubed-Mini-仓库名（每个仓库一个项目） |
| 项目标识 | `pycubed-mini`-仓库名（英文小写） |
| 项目简介 | PyCubed 的 PocketQube 版本组织主页，开源 avionics-mainboard 主控板与 avionics-batteryboard 电池板，延续 PyCubed 的开源 OBC 标杆路线。镜像收录自 https://github.com/PyCubed-Mini 组织名下仓库，License：avionics-mainboard、avionics-batteryboard 均未检测到 LICENSE 文件 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| avionics-mainboard | https://github.com/PyCubed-Mini/avionics-mainboard |
| avionics-batteryboard | https://github.com/PyCubed-Mini/avionics-batteryboard |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| PyCubed-Mini/avionics-mainboard | ⚠️ 未检测到 LICENSE 文件（仓库存在） |
| PyCubed-Mini/avionics-batteryboard | ⚠️ 未检测到 LICENSE 文件（仓库存在） |
- 结果：⚠️ 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支）
- 结论：**不可镜像代码**。公开仓库不等于授权，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
