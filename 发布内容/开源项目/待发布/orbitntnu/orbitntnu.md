# OrbitNTNU

> 板块：项目管理 / orbitntnu
> 来源：https://github.com/OrbitNTNU
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

挪威科技大学学生卫星组织主页（FRAMSAT 系列），包含 TMS570 星务机 Zephyr RTOS 移植、CyanoSat-2026 项目与反作用轮设计等仓库。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | OrbitNTNU-仓库名（每个仓库一个项目） |
| 项目标识 | `orbitntnu`-仓库名（英文小写） |
| 项目简介 | 挪威科技大学学生卫星组织主页（FRAMSAT 系列），包含 TMS570 星务机 Zephyr RTOS 移植、CyanoSat-2026 项目与反作用轮设计等仓库。镜像收录自 https://github.com/OrbitNTNU 组织名下仓库，License：cyanosat-2026 未检测到 LICENSE 文件，另 2 个重点仓库当前无法访问 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| TMS570 OBC Zephyr 移植 | https://github.com/OrbitNTNU/tms570-zephyr |
| CyanoSat-2026 | https://github.com/OrbitNTNU/cyanosat-2026 |
| 反作用轮 | https://github.com/OrbitNTNU/reaction-wheel |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
| 仓库 | 结果 |
| --- | --- |
| OrbitNTNU/cyanosat-2026 | ⚠️ 未检测到 LICENSE 文件（仓库存在） |
| OrbitNTNU/reaction-wheel | ❓ 仓库无法访问（404，可能改名/删除/私有） |
| OrbitNTNU/tms570-zephyr | ❓ 仓库无法访问（404，可能改名/删除/私有） |
- 结论：cyanosat-2026 **不可镜像代码**（无 LICENSE，只能收录链接）；其余仓库需人工核查后再决定
