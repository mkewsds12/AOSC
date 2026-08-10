# NASA CryptoLib

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/CryptoLib
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

NASA CryptoLib 是 NASA 开源的 CCSDS SDLS（Space Data Link Security）空间数据链路安全加密库，以 C 语言实现，为星地链路提供认证、加密等安全服务，是构建符合 CCSDS 安全标准测控链路的重要参考实现。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/nasa/CryptoLib.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `NASA CryptoLib` |
| 项目标识 | `cryptolib` |
| 项目简介 | NASA 开源的 CCSDS SDLS 空间数据链路安全加密库（C 实现），为星地链路提供认证、加密等安全服务，是构建符合 CCSDS 安全标准测控链路的重要参考。镜像收录自 https://github.com/nasa/CryptoLib，License：NASA Open Source Agreement 1.3 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | C |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：NASA Open Source Agreement 1.3（LICENSE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
