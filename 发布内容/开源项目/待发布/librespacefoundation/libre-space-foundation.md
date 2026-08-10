# Libre Space Foundation

> 板块：项目管理 / Libre Space Foundation
> 来源：https://gitlab.com/librespacefoundation
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

全球最大的开源卫星组织入口，名下 30+ 项目覆盖卫星整星（UPSat、QUBIK）、地面站网络（SatNOGS）、信号处理（SIDLOC、PHASMA）、运载（cronos-rocket）等全链条，是开源航天生态的核心。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | Libre Space Foundation-仓库名（每个仓库一个项目） |
| 项目标识 | `libre-space-foundation`-仓库名（英文小写） |
| 项目简介 | 全球最大的开源卫星组织入口，名下 30+ 项目覆盖卫星整星（UPSat、QUBIK）、地面站网络（SatNOGS）、信号处理（SIDLOC、PHASMA）、运载（cronos-rocket）等全链条，是开源航天生态的核心。镜像收录自 https://gitlab.com/librespacefoundation 组织名下仓库，License：各子组代表仓多为 GPL-3.0/AGPL-3.0/LGPL-3.0，phasma、libresat 未检测到 LICENSE 文件，详见文末核查节 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| UPSat | https://gitlab.com/librespacefoundation/upsat |
| SatNOGS | https://gitlab.com/librespacefoundation/satnogs |
| SIDLOC | https://gitlab.com/librespacefoundation/sidloc |
| QUBIK | https://gitlab.com/librespacefoundation/qubik |
| PHASMA | https://gitlab.com/librespacefoundation/phasma |
| Polaris | https://gitlab.com/librespacefoundation/polaris |
| HELEO | https://gitlab.com/librespacefoundation/heleo |
| libresat | https://gitlab.com/librespacefoundation/libresat |
| cronos-rocket | https://gitlab.com/librespacefoundation/cronos-rocket |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
原列出的仓库路径多已重组为子组，下表为各子组代表仓库的核查结果：

| 原路径 | 现状 | 代表仓库结果 |
| --- | --- | --- |
| upsat | 已重组为子组 | upsat-obc-software：GPL-3.0（LICENSE，master） |
| qubik | 已重组为子组 | qubik-comms-sw：GPL-3.0（LICENSE，master） |
| satnogs | 已重组为子组 | satnogs-mcs：AGPL-3.0（LICENSE，main） |
| sidloc | 已重组为子组 | sidloc-mcu-sw：GPL-3.0（LICENSE，master） |
| phasma | 已重组为子组 | phasma-obc-software：⚠️ 未检测到 LICENSE 文件 |
| polaris | 已重组为子组 | betsi：LGPL-3.0（LICENSE，master） |
| heleo | 已重组为子组 | heleo-satnogs-comms-mcu-sw：GPL-3.0（LICENSE，main） |
| libresat | 项目现为 libresat-i | libresat-i：⚠️ 未检测到 LICENSE 文件 |
| cronos-rocket | 已重组为子组 | avionics/apogee-detection：GPL-3.0（LICENSE，main） |

- 结论：GPL/LGPL/AGPL 系仓库许可证明确，可镜像；镜像时保留 LICENSE 与版权声明，衍生/分发需开源同等授权（镜像只读展示合规）。phasma、libresat 对应仓库**不可镜像代码**，只能收录链接。镜像 URL 需按重组后的实际仓库路径更新
