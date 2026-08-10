# Space Cloud

> 板块：项目管理 / spacecloud-io
> 来源：https://github.com/spacecloud-io/space-cloud
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

Space Cloud 是一个开源的「太空云」Serverless 框架，基于 Kubernetes 运行，提供数据库、文件存储、事件驱动与微服务编排的统一 API 网关能力，可快速搭建后端服务而无需手写服务代码。名称与航天主题契合，可作为星地应用服务快速开发的基础设施参考。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/spacecloud-io/space-cloud.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `Space Cloud` |
| 项目标识 | `space-cloud` |
| 项目简介 | 开源 Serverless 框架，基于 Kubernetes，提供数据库、文件存储、事件驱动与微服务编排的统一 API 网关能力，可快速搭建后端服务。镜像收录自 https://github.com/spacecloud-io/space-cloud，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 应用服务 |
| 项目语言 | Go |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「应用服务」→ 保存

## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE，master 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
