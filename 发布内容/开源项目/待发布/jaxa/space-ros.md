# Space ROS（RACS2）

> 板块：项目管理 / jaxa
> 来源：https://github.com/jaxa/racs2_bridge
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

JAXA 开源的 RACS2（Robot-to-Avionics Communication System 2）桥接软件 racs2_bridge，实现 ROS2 与 cFS 飞行软件之间的消息互通，是机器人操作系统与星务软件融合的参考实现；同生态可参考 space_ros_turtlebot3_demo 与 space_robotics_bench。镜像收录自 https://github.com/jaxa/racs2_bridge，License：Apache-2.0（主仓库 racs2_bridge）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/jaxa/racs2_bridge.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明）；下方列出的参考仓库可按需单独导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Space ROS（RACS2）` |
| 项目标识 | `racs2-bridge` |
| 项目简介 | JAXA 开源的 RACS2 桥接软件，实现 ROS2 与 cFS 飞行软件消息互通，是机器人系统与星务软件融合的参考实现。镜像收录自 https://github.com/jaxa/racs2_bridge，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | 以源仓库为准 |

## 同生态参考仓库（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| racs2_bridge（ROS2↔cFS 桥接，主收录） | https://github.com/jaxa/racs2_bridge |
| space_ros_turtlebot3_demo | https://github.com/jaxa/space_ros_turtlebot3_demo |
| space_robotics_bench | https://github.com/jaxa/space_robotics_bench |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE，main 分支；主收录仓库 jaxa/racs2_bridge）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。参考仓库 space_ros_turtlebot3_demo、space_robotics_bench 未单独核查，如需镜像请逐仓库核查
