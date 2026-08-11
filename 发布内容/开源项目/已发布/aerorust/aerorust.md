# AeroRust 姿控生态

> 板块：项目管理 / aerorust
> 来源：https://github.com/AeroRust
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

AeroRust 是 Rust 语言航空航天开源社区组织，维护多个 ADCS（姿态确定与控制）与星上组件相关仓库，覆盖导航滤波、参考坐标系、天体动力学等方向，是 Rust 星上软件生态的重要入口。镜像收录自 https://github.com/AeroRust ，License 以源仓库 LICENSE 为准。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入 |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `AeroRust 姿控生态` |
| 项目标识 | `aerorust` |
| 项目简介 | Rust 航空航天开源社区组织主页，维护 ADCS、导航滤波、天体动力学等多个星上组件仓库，是 Rust 星上软件生态入口。镜像收录自 https://github.com/AeroRust ，License 以源仓库 LICENSE 为准 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 姿控算法 |
| 项目语言 | Rust |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「姿控算法」→ 保存

## 重点仓库清单（需逐个导入，仓库名以实际为准）

| 仓库名 | URL |
|--------|-----|
| ADCS 相关仓库（如 adcs，仓库名以实际为准） | https://github.com/AeroRust/adcs |
| 导航/滤波相关仓库（仓库名以实际为准） | https://github.com/AeroRust/navigation |
| 天体动力学相关仓库（仓库名以实际为准） | https://github.com/AeroRust/astrodynamics |

> 以上为示意性重点仓库方向，实际仓库名与数量需人工登录 https://github.com/AeroRust 核对后确定。

## 许可证核查（2026-08-10）
- 结果：❓ 文末所列重点仓库均无法访问（可能改名/删除/私有）

| 仓库 | 探测结果 |
|------|---------|
| https://github.com/AeroRust/adcs | ❓ 仓库无法访问（404，可能改名/删除/私有） |
| https://github.com/AeroRust/navigation | ❓ 仓库无法访问（404，可能改名/删除/私有） |
| https://github.com/AeroRust/astrodynamics | ❓ 仓库无法访问（404，可能改名/删除/私有） |

- 结论：需人工核查后再决定。文件已注明仓库名为示意性，需人工登录 https://github.com/AeroRust 核对实际仓库清单后，逐个按仓库核查许可证；未确认许可证前不得镜像任何代码
