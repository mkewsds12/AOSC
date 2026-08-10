# TMTC Commander

> 板块：项目管理 / robamu-org
> 来源：https://github.com/robamu-org/tmtccmd
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

TMTC Commander 是 Python 编写的遥测遥控（TMTC）框架，支持 PUS 服务、CCSDS 空间包与 CFDP 文件传输协议，提供命令行与 GUI 界面，可用于卫星组件与地面系统的 TMTC 联调测试，大幅降低 ECSS 标准协议的测试门槛。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | `https://github.com/robamu-org/tmtccmd.git`（GitHub/GitLab/Gitee 地址末尾加 .git；若来源不是 git 仓库见下方说明） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `TMTC Commander` |
| 项目标识 | `tmtccmd` |
| 项目简介 | Python 遥测遥控框架，支持 PUS/CCSDS/CFDP 协议，含命令行与 GUI，可用于卫星组件与地面系统的 TMTC 联调测试，降低 ECSS 标准协议测试门槛。镜像收录自 https://github.com/robamu-org/tmtccmd，License：Apache-2.0 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 测控通信 |
| 项目语言 | Python |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：Apache-2.0（LICENSE-APACHE，main 分支）
- 结论：许可证明确，可镜像；镜像时保留 LICENSE 与版权声明
