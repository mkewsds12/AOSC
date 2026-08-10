# SatNOGS COMMS

> 板块：项目管理 / Libre Space Foundation
> 来源：https://gitlab.com/librespacefoundation/satnogs-comms
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

SatNOGS COMMS 是 Libre Space Foundation 开源的卫星通信子系统，面向纳卫星/立方星任务，集成收发链路与星载通信管理功能，与 SatNOGS 地面站网络生态配套使用。项目包含硬件与固件设计，为开源立方星提供完整的星地通信解决方案。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://gitlab.com/librespacefoundation/satnogs-comms.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `SatNOGS COMMS` |
| 项目标识 | `satnogs-comms` |
| 项目简介 | SatNOGS 开源通信子系统，面向纳卫星/立方星任务，含收发链路与通信管理，与 SatNOGS 地面站网络生态配套，提供完整开源星地通信方案。镜像收录自 https://gitlab.com/librespacefoundation/satnogs-comms，License：无法确认（仓库无法访问） |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：❓ 仓库无法访问（GitLab API 返回 404 Project Not Found，可能已删除/改名/设为私有；raw 地址重定向到验证页，无法探测 LICENSE）
- 结论：需人工核查后再决定
