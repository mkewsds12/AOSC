# OpenC3（原 COSMOS）

> 板块：项目管理 / openc3
> 来源：https://github.com/OpenC3/cosmos
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

OpenC3 COSMOS 是 Ball Aerospace COSMOS 的社区版，提供遥测显示、指令发送、脚本执行与接口适配的全套地面测控能力，配置化程度高，适用于各类卫星地面测试与在轨运控。镜像收录自 https://github.com/OpenC3/cosmos，License：待人工核查（OpenC3 Builder's License 自定义条款）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/OpenC3/cosmos.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `OpenC3（原 COSMOS）` |
| 项目标识 | `openc3-cosmos` |
| 项目简介 | Ball COSMOS 社区版，遥测显示、指令发送、脚本执行全套地面测控能力，配置化程度高。镜像收录自 https://github.com/OpenC3/cosmos，License：待人工核查（OpenC3 Builder's License 自定义条款）。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：❓ 存在 LICENSE 但为自定义许可（LICENSE.md，main 分支），原文开头：「OpenC3 Builder's License / Acceptance / By using the software, you agree to all of the terms and conditions below」，非 OSI 标准许可证，可能含使用限制
- 结论：需人工核查条款全文后再决定；在确认允许再分发前**不建议镜像代码**，专区可先只收录官方链接
