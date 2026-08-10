# spacecan_lib

> 板块：项目管理 / jahaziellem
> 来源：https://github.com/JahazielLem/spacecan_lib
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

spacecan_lib 是 SpaceCAN 星载总线协议的 C 语言开源实现，SpaceCAN 在 CAN 总线之上增加了可靠传输与网络层机制，适合立方星星务与各分系统间通信。项目附带仿真支持，便于在无硬件环境下开发验证。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/JahazielLem/spacecan_lib.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `spacecan_lib` |
| 项目标识 | `spacecan-lib` |
| 项目简介 | SpaceCAN 星载总线协议 C 实现，在 CAN 之上增加可靠传输与网络层机制，适合立方星星务与各分系统间通信，附带仿真支持便于无硬件开发验证。镜像收录自 https://github.com/JahazielLem/spacecan_lib，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明；GPL-3.0：衍生/分发需开源同等授权，镜像只读展示合规
