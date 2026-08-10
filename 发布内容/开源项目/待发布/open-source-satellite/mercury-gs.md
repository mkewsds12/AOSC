# Mercury-GS

> 板块：项目管理 / open-source-satellite
> 来源：https://github.com/Open-Source-Satellite/Mercury-GS
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Mercury-GS 是 Open-Source-Satellite 项目的地面软件，用于发射前实验室环境中与航天器进行指令交互与测试验证，帮助研制团队在整星集成阶段完成通信链路检查与功能测试。镜像收录自 https://github.com/Open-Source-Satellite/Mercury-GS，License：待人工核查（自定义许可，见 LICENSE.md 外链条款）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/Open-Source-Satellite/Mercury-GS.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Mercury-GS` |
| 项目标识 | `mercury-gs` |
| 项目简介 | 发射前实验室环境与航天器交互的开源地面软件，支撑整星集成阶段通信链路检查与功能测试。镜像收录自 https://github.com/Open-Source-Satellite/Mercury-GS，License：待人工核查（自定义许可，见 LICENSE.md 外链条款）。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：❓ 存在 LICENSE 但类型不明（LICENSE.md，main 分支）。原文仅指向外部条款：「All code within this repository is subject to the following license: www.kispe.co.uk/projectlicenses/RA2001001003」，为自定义/专有许可，未授予明确开源权利
- 结论：需人工核查后再决定；在确认授权前**不建议镜像代码**，专区可先只收录官方链接
