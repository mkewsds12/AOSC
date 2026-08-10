# OpenSpaceCode 嵌入式 CCSDS 系列

> 板块：项目管理 / OpenSpaceCode
> 来源：https://github.com/OpenSpaceCode
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

OpenSpaceCode 是一个专注极简嵌入式 CCSDS/ECSS 协议 C 实现的开源组织，涵盖 PUS 服务、空间包、数据链路协议、CFDP、SpaceWire、CUC 时间码等星载通信核心组件，另附 OpenSpaceEGSE 桌面测试工具，适合星务软件与地面测试系统直接集成。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | 按各仓库实际名称（如 `EmbeddedPUS`） |
| 项目标识 | 按各仓库名转小写（如 `embeddedpus`） |
| 项目简介 | 极简嵌入式 CCSDS/ECSS 协议 C 实现（按各仓库功能描述）。镜像收录自 https://github.com/OpenSpaceCode，License：Apache-2.0（各仓库均为 Apache-2.0，见文末核查表） |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | C |

## 重点仓库清单（仓库名以实际为准）

| 仓库名 | URL |
|--------|-----|
| EmbeddedPUS | https://github.com/OpenSpaceCode/EmbeddedPUS |
| EmbeddedSpacePacket | https://github.com/OpenSpaceCode/EmbeddedSpacePacket |
| EmbeddedSDLP | https://github.com/OpenSpaceCode/EmbeddedSDLP |
| EmbeddedCFDP | https://github.com/OpenSpaceCode/EmbeddedCFDP |
| EmbeddedSpaceWire | https://github.com/OpenSpaceCode/EmbeddedSpaceWire |
| EmbeddedCUCTime | https://github.com/OpenSpaceCode/EmbeddedCUCTime |
| OpenSpaceEGSE | https://github.com/OpenSpaceCode/OpenSpaceEGSE |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）

组织主页类文件，逐仓库核查结果：

| 仓库 | LICENSE | 结果 |
| --- | --- | --- |
| EmbeddedPUS | LICENSE，main 分支 | Apache-2.0 |
| EmbeddedSpacePacket | LICENSE，main 分支 | Apache-2.0 |
| EmbeddedSDLP | LICENSE，main 分支 | Apache-2.0 |
| EmbeddedCFDP | LICENSE，main 分支 | Apache-2.0 |
| EmbeddedSpaceWire | LICENSE，main 分支 | Apache-2.0 |
| EmbeddedCUCTime | LICENSE，main 分支 | Apache-2.0 |
| OpenSpaceEGSE | LICENSE，main 分支 | Apache-2.0 |

- 结论：全部仓库许可证明确（Apache-2.0），可镜像；镜像时保留各仓库 LICENSE 与版权声明
