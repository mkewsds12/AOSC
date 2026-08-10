# SpaceOdyssey-QEMU-AVR32

> 板块：项目管理 / cispa-syssec
> 来源：https://github.com/CISPA-SysSec/SpaceOdyssey-QEMU-AVR32
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

SpaceOdyssey-QEMU-AVR32 是 CISPA 系统安全团队开源的 OPS-SAT 星载软件 QEMU 仿真器，可在无硬件条件下全系统仿真运行 ESA OPS-SAT 卫星星载软件，支撑地面测试与航天安全研究。镜像收录自 https://github.com/CISPA-SysSec/SpaceOdyssey-QEMU-AVR32，License：GPL-2.0（QEMU 组合许可）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/CISPA-SysSec/SpaceOdyssey-QEMU-AVR32.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `SpaceOdyssey-QEMU-AVR32` |
| 项目标识 | `spaceodyssey-qemu-avr32` |
| 项目简介 | OPS-SAT 星载软件 QEMU 仿真器，无硬件全系统仿真运行卫星软件，支撑地面测试与安全研究。镜像收录自 https://github.com/CISPA-SysSec/SpaceOdyssey-QEMU-AVR32，License：GPL-2.0（QEMU 组合许可）。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-2.0（LICENSE，master 分支；QEMU 组合许可——仿真器整体 GPL-2.0，部分源文件为 GPL 兼容许可）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。GPL-2.0：衍生/分发需开源同等授权；镜像只读展示合规
