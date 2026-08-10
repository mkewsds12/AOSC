# space_packet_parser

> 板块：项目管理 / lasp
> 来源：https://github.com/lasp/space_packet_parser
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

space_packet_parser 是 LASP（科罗拉多大学大气与空间物理实验室）开源的通用 CCSDS 空间数据包解析工具，基于 XTCE（XML 遥测与指令交换）标准描述文件进行解码，无需手写解析代码即可适配不同任务的遥测格式，适合处理多型号、多任务的遥测数据。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/lasp/space_packet_parser.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `space_packet_parser` |
| 项目标识 | `space-packet-parser` |
| 项目简介 | LASP 开源的通用 CCSDS 空间数据包解析工具，基于 XTCE 标准描述文件解码遥测数据，无需手写解析代码即可适配不同任务格式。镜像收录自 https://github.com/lasp/space_packet_parser，License：BSD-3-Clause |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 数据管理 |
| 项目语言 | Python |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「数据管理」→ 保存

## 许可证核查（2026-08-10）
- 结果：BSD-3-Clause（LICENSE.txt，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
