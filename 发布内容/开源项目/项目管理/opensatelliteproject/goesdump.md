# goesdump

> 板块：项目管理 / opensatelliteproject
> 来源：https://github.com/opensatelliteproject/goesdump
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

goesdump 是 Open Satellite Project 旗下的 GOES 气象卫星数据转储与解调工具，可配合 SDR 接收 GOES 系列卫星 HRIT/EMWIN 下行链路数据，解调并还原出气象云图与文本产品。是低成本气象卫星直接接收方案的常用开源组件。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/opensatelliteproject/goesdump.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `goesdump` |
| 项目标识 | `goesdump` |
| 项目简介 | Open Satellite Project 的 GOES 气象卫星数据转储与解调工具，配合 SDR 接收 HRIT/EMWIN 下行数据并还原云图与文本产品。镜像收录自 https://github.com/opensatelliteproject/goesdump，License：未检测到 LICENSE 文件 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 应用服务 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「应用服务」→ 保存

## 许可证核查（2026-08-10）
- 结果：⚠️ 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYING.md/COPYRIGHT/UNLICENSE，main/master 分支；GitHub API license 字段为 null）
- 结论：**不可镜像代码**。公开仓库不等于授权，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
