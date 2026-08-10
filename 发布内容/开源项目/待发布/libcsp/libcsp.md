# libcsp（CubeSat Space Protocol）

> 板块：项目管理 / libcsp
> 来源：https://github.com/libcsp/libcsp
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

libcsp 是专为立方星等嵌入式航天器设计的网络层协议栈，提供类似 TCP/IP 的分层通信抽象，支持 CAN、串口、KISS 等多种链路传输。它是社区最活跃的星载通信协议之一，已在大量立方星任务中实际飞行验证，资源占用低，适合星务计算机部署。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/libcsp/libcsp.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `libcsp（CubeSat Space Protocol）` |
| 项目标识 | `libcsp` |
| 项目简介 | 立方星专用网络层协议栈，支持 CAN、串口、KISS 等链路，低资源占用，多项任务飞行验证，社区最活跃的星载通信协议之一。镜像收录自 https://github.com/libcsp/libcsp，License：MIT |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：MIT（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
