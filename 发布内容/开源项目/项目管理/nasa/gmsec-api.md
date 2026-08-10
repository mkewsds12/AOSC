# GMSEC

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/GMSEC_API
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

GMSEC（Goddard Mission Services Evolution Center）是 NASA 戈达德航天中心开源的消息总线 API，提供多语言绑定的标准化消息中间件接口，实现地面系统各组件间、星地之间的解耦通信。镜像收录自 https://github.com/nasa/GMSEC_API，License：NOSA-1.3（NASA Open Source Agreement）。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/nasa/GMSEC_API.git` |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `GMSEC` |
| 项目标识 | `gmsec-api` |
| 项目简介 | NASA 戈达德消息总线 API，多语言绑定的标准化消息中间件接口，实现星地解耦通信。镜像收录自 https://github.com/nasa/GMSEC_API，License：NOSA-1.3（NASA Open Source Agreement）。 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 地面测试 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「地面测试」→ 保存

## 许可证核查（2026-08-10）
- 结果：NOSA-1.3（NASA Open Source Agreement，仓库根目录 NOSA.pdf，master 分支）
- 结论：许可证明确（OSI 批准的 NASA 协议），可镜像；镜像时保留 NOSA.pdf 与版权声明。NOSA：衍生作品分发需开源并保留协议文本；镜像只读展示合规
