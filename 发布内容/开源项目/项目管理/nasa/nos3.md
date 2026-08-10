# NASA NOS3

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/nos3
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

NOS3（NASA Operational Simulator for Small Satellites）是 NASA 开源的小卫星仿真环境，将星载飞行软件（FSW）、地面软件（GSW）与动力学/部件仿真器一体化集成，支撑 STF-1 任务，可在无硬件条件下完成整星软件测试验证。镜像收录自 https://github.com/nasa/nos3，License：NOSA-1.3（NASA Open Source Agreement）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/nasa/nos3.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NASA NOS3` |
| 项目标识 | `nos3` |
| 项目简介 | NASA 开源小卫星仿真环境，FSW+GSW+仿真器一体化，无硬件完成整星软件测试。镜像收录自 https://github.com/nasa/nos3，License：NOSA-1.3（NASA Open Source Agreement）。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：NOSA-1.3（NASA Open Source Agreement Version 1.3，LICENSE，main 分支）
- 结论：许可证明确（OSI 批准的 NASA 协议），可镜像；镜像时保留 LICENSE 与版权声明。NOSA：衍生作品分发需开源并保留协议文本；镜像只读展示合规
