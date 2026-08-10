# PW-Sat2

> 板块：项目管理 / PW-Sat2（社区镜像）
> 来源：https://github.com/PW-Sat2
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

波兰华沙理工大学学生卫星组织主页，PW-Sat2 全套开源（OBC、EPS 等），包含太阳帆离轨实验载荷，是学生立方星工程实践的典范。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | PW-Sat2-仓库名（每个仓库一个项目） |
| 项目标识 | `pw-sat2`-仓库名（英文小写） |
| 项目简介 | 波兰华沙理工大学学生卫星组织主页，PW-Sat2 全套开源（OBC、EPS 等），包含太阳帆离轨实验载荷，是学生立方星工程实践的典范。镜像收录自 https://github.com/PW-Sat2 组织名下仓库，License：PWSat2OBC 为 AGPL-3.0，其余 3 个重点仓库当前无法访问 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| PWSat2OBC | https://github.com/PW-Sat2/PWSat2OBC |
| PWSat2EPS | https://github.com/PW-Sat2/PWSat2EPS |
| PWSat2ADCS | https://github.com/PW-Sat2/PWSat2ADCS |
| PWSat2COMMS | https://github.com/PW-Sat2/PWSat2COMMS |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| PW-Sat2/PWSat2OBC | AGPL-3.0（LICENSE.txt，master 分支） |
| PW-Sat2/PWSat2ADCS | ❓ 仓库无法访问（404，可能改名/删除/私有） |
| PW-Sat2/PWSat2COMMS | ❓ 仓库无法访问（404，可能改名/删除/私有） |
| PW-Sat2/PWSat2EPS | ❓ 仓库无法访问（404，可能改名/删除/私有） |
- 结论：PWSat2OBC 许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。AGPL-3.0：衍生/网络分发需开源同等授权；镜像只读展示合规。其余仓库需人工核查（实际代码多在 PWSat2OBC 主仓）后再决定
