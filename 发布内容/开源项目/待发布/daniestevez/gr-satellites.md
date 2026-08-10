# gr-satellites

> 板块：项目管理 / daniestevez
> 来源：https://github.com/daniestevez/gr-satellites
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

gr-satellites 是 GNU Radio 上的业余卫星解码器集合，由 Daniel Estévez 维护，覆盖大量立方星与业余卫星的遥测协议，支持实时解调与录音回放解码，遥测结果可直接提交 SatNOGS 数据库。是搭建卫星接收地面站最实用的开源工具之一。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/daniestevez/gr-satellites.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `gr-satellites` |
| 项目标识 | `gr-satellites` |
| 项目简介 | GNU Radio 业余卫星解码器集合，覆盖大量立方星遥测协议，支持实时解调与录音回放，遥测可提交 SatNOGS 数据库，是搭建卫星地面站的实用工具。镜像收录自 https://github.com/daniestevez/gr-satellites，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | Python |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明；GPL-3.0：衍生/分发需开源同等授权，镜像只读展示合规
