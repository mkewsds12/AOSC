# PWSat2OBC

> 板块：项目管理 / PW-Sat2（社区镜像）
> 来源：https://github.com/PW-Sat2/PWSat2OBC
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

PWSat2OBC 是波兰 PW-Sat2 立方星的星载计算机（OBC）飞行软件，完整开源了星务调度、遥测采集、存储管理等核心功能，是经过在轨验证的星务软件参考实现。镜像收录自 https://github.com/PW-Sat2/PWSat2OBC，License：AGPL-3.0。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/PW-Sat2/PWSat2OBC.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `PWSat2OBC` |
| 项目标识 | `pwsat2obc` |
| 项目简介 | 波兰 PW-Sat2 立方星星载计算机飞行软件，完整开源星务调度、遥测与存储管理，经在轨验证。镜像收录自 https://github.com/PW-Sat2/PWSat2OBC，License：AGPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）
- 结果：AGPL-3.0（LICENSE.txt，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。AGPL-3.0：衍生/分发乃至网络提供服务均需开源同等授权；镜像只读展示合规
