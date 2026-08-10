# gr-leo

> 板块：项目管理 / Libre Space Foundation
> 来源：https://gitlab.com/librespacefoundation/gr-leo
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

gr-leo 是 Libre Space Foundation 开源的 GNU Radio 信道模拟器，可模拟低轨卫星与地面站之间的空间信道，包括多普勒频移、自由空间损耗、大气衰减等效应，用于在实验室环境下验证卫星通信链路，无需真实过境即可测试地面站接收系统。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://gitlab.com/librespacefoundation/gr-leo.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `gr-leo` |
| 项目标识 | `gr-leo` |
| 项目简介 | GNU Radio 信道模拟器，模拟低轨卫星与地面站间的多普勒频移、自由空间损耗、大气衰减等效应，可在实验室验证卫星通信链路与地面站接收系统。镜像收录自 https://gitlab.com/librespacefoundation/gr-leo，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明；GPL-3.0：衍生/分发需开源同等授权，镜像只读展示合规
