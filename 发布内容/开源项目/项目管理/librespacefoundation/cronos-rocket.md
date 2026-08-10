# cronos-rocket

> 板块：项目管理 / Libre Space Foundation
> 来源：https://gitlab.com/librespacefoundation/cronos-rocket
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Libre Space Foundation 的开源火箭项目，作为开源卫星的配套运输工具参考。设计与代码开源，可用于了解开源运载工具的工程实践。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://gitlab.com/librespacefoundation/cronos-rocket.git`（源地址末尾加 .git） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | cronos-rocket |
| 项目标识 | `cronos-rocket` |
| 项目简介 | Libre Space Foundation 的开源火箭项目，作为开源卫星的配套运输工具参考。设计与代码开源，可用于了解开源运载工具的工程实践。镜像收录自 https://gitlab.com/librespacefoundation/cronos-rocket，License：GPL-3.0（avionics/apogee-detection 仓） |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，main 分支；代表仓 cronos-rocket/avionics/apogee-detection）
- 备注：原 URL `gitlab.com/librespacefoundation/cronos-rocket` 已重组为子组主页，实际代码仓位于其子组下（如 avionics/apogee-detection），镜像 URL 需相应更新
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规
