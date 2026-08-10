# PyCubed

> 板块：项目管理 / pycubed
> 来源：https://github.com/pycubed/hardware
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

KiCad 开源星载计算机（OBC）标杆项目，采用 PC/104 标准布局，软硬件全套开源。已被多颗实际立方星采用，是 CubeSat 主控板设计的首选参考。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/pycubed/hardware.git`（源地址末尾加 .git） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | PyCubed |
| 项目标识 | `pycubed` |
| 项目简介 | KiCad 开源星载计算机（OBC）标杆项目，采用 PC/104 标准布局，软硬件全套开源。已被多颗实际立方星采用，是 CubeSat 主控板设计的首选参考。镜像收录自 https://github.com/pycubed/hardware，未检测到 LICENSE 文件 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
- 结果：⚠️ 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支；仓库存在）
- 结论：**不可镜像代码**。公开仓库不等于授权，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
