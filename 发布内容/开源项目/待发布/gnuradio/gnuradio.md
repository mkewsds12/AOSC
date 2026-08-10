# GNU Radio

> 板块：项目管理 / gnuradio
> 来源：https://github.com/gnuradio/gnuradio
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

GNU Radio 是最主流的开源软件无线电（SDR）开发框架，提供信号处理模块库与图形化流程图编排能力，可快速搭建调制解调、解码、频谱分析等系统。它是卫星解调生态的基石，gr-satellites、gr-satnogs 等大量卫星解码模块均基于其构建，配合 USRP、RTL-SDR、HackRF 等硬件广泛用于卫星地面站。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/gnuradio/gnuradio.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `GNU Radio` |
| 项目标识 | `gnuradio` |
| 项目简介 | 开源软件无线电框架，提供信号处理模块库与流程图编排，是卫星解调生态的基石，gr-satellites 等大量卫星解码模块均基于其构建，广泛用于卫星地面站。镜像收录自 https://github.com/gnuradio/gnuradio，License：GPL-3.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | C++ |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：GPL-3.0（COPYING，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明；GPL-3.0：衍生/分发需开源同等授权，镜像只读展示合规
