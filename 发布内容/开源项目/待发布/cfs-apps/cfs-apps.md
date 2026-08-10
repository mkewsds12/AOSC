# cfs-apps 系列

> 板块：项目管理 / cfs-apps
> 来源：https://github.com/cfs-apps
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

cfs-apps 是 cFS 社区应用开源组织主页，汇集 jmsg_mqtt（MQTT 消息桥）、mqtt_lib、pi_iolib（树莓派 IO）、pl_sim（载荷模拟）、bc42_ctrl（42 仿真器姿控接入 cFS）等社区应用，扩展了 cFS 在物联网接口、载荷与仿真集成方面的能力。镜像收录自 https://github.com/cfs-apps，License 以各源仓库 LICENSE 为准。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库单独建 GitLink 项目） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | 按各仓库名命名，如 `jmsg_mqtt` |
| 项目标识 | 各仓库英文标识，如 `jmsg-mqtt`、`pl-sim` |
| 项目简介 | 按各仓库说明填写，末尾含「镜像收录自 https://github.com/cfs-apps，License 以源仓库 LICENSE 为准」 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | 以源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| jmsg_mqtt（MQTT 消息桥） | https://github.com/cfs-apps/jmsg_mqtt |
| mqtt_lib | https://github.com/cfs-apps/mqtt_lib |
| pi_iolib（树莓派 IO） | https://github.com/cfs-apps/pi_iolib |
| pl_sim（载荷模拟） | https://github.com/cfs-apps/pl_sim |
| bc42_ctrl（42 姿控接入 cFS） | https://github.com/cfs-apps/bc42_ctrl |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）

| 仓库 | 许可证 | LICENSE 文件 / 分支 | 结论 |
|------|--------|--------------------|------|
| cfs-apps/bc42_ctrl | AGPL-3.0 | LICENSE / main | 可镜像；AGPL-3.0：衍生/分发乃至网络提供服务均需开源同等授权；镜像只读展示合规 |
| cfs-apps/jmsg_mqtt | GPL-3.0（含附加条款） | LICENSE / main | 可镜像；GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规 |
| cfs-apps/mqtt_lib | GPL-3.0（含附加条款） | LICENSE / main | 可镜像；GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规 |
| cfs-apps/pi_iolib | GPL-3.0（含附加条款） | LICENSE / main | 可镜像；GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规 |
| cfs-apps/pl_sim | GPL-3.0（含附加条款） | LICENSE / main | 可镜像；GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规 |

- 结论：5 个重点仓库许可证明确，可镜像；镜像时保留各仓库 LICENSE 与版权声明
