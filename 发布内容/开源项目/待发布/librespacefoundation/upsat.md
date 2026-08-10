# UPSat

> 板块：项目管理 / Libre Space Foundation
> 来源：https://gitlab.com/librespacefoundation/upsat
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Libre Space Foundation 打造的全球第一颗完全开源卫星，2017 年发射的 2U 立方星。OBC、EPS、ADCS、COMMS 等分系统的软硬件全部开源，是整星级开源设计的里程碑项目。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://gitlab.com/librespacefoundation/upsat.git`（源地址末尾加 .git） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | UPSat |
| 项目标识 | `upsat` |
| 项目简介 | Libre Space Foundation 打造的全球第一颗完全开源卫星，2017 年发射的 2U 立方星。OBC、EPS、ADCS、COMMS 等分系统的软硬件全部开源，是整星级开源设计的里程碑项目。镜像收录自 https://gitlab.com/librespacefoundation/upsat，License：GPL-3.0（主仓 upsat-obc-software） |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，master 分支；主仓 upsat-obc-software）
- 备注：原 URL `gitlab.com/librespacefoundation/upsat` 已重组为子组主页，实际代码仓位于 `librespacefoundation/upsat/upsat-obc-software` 等子组仓库，镜像 URL 需相应更新
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规
