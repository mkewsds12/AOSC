# NASA cFS 工具生态

> 板块：项目管理 / NASA
> 来源：https://github.com/nasa/CTF
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

NASA cFS 官方配套工具系列仓库入口，涵盖 CTF（cFS 测试框架）、CCDD（命令数据字典）、cFS-GroundSystem（官方地面系统）、elf2cfetbl、gen_msgids、tblCRCTool、SIL、tvsio 等，覆盖星务软件开发、测试与地面支持全流程。镜像收录自 https://github.com/nasa/CTF，License 以各源仓库 LICENSE 为准。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为系列仓库入口（NASA 组织下多个仓库），需按下方列出的重点仓库逐个导入（每个仓库单独建 GitLink 项目） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | 按各仓库名命名，如 `NASA CTF` |
| 项目标识 | 各仓库英文标识，如 `ctf`、`ccdd`、`cfs-groundsystem` |
| 项目简介 | 按各仓库说明填写，末尾含「镜像收录自 https://github.com/nasa/{仓库名}，License 以源仓库 LICENSE 为准」 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 星务处理 |
| 项目语言 | 以源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| CTF（cFS 测试框架） | https://github.com/nasa/CTF |
| CCDD（命令数据字典） | https://github.com/nasa/CCDD |
| cFS-GroundSystem（官方地面系统） | https://github.com/nasa/cFS-GroundSystem |
| elf2cfetbl | https://github.com/nasa/elf2cfetbl |
| gen_msgids | https://github.com/nasa/gen_msgids |
| tblCRCTool | https://github.com/nasa/tblCRCTool |
| SIL（软件在环仿真） | https://github.com/nasa/SIL |
| tvsio | https://github.com/nasa/tvsio |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「星务处理」→ 保存


## 许可证核查（2026-08-10）

| 仓库 | 许可证 | LICENSE 文件 / 分支 | 结论 |
|------|--------|--------------------|------|
| nasa/CCDD | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| nasa/CTF | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| nasa/SIL | NASA-1.3（NASA Open Source Agreement v1.3） | license.md / master | 可镜像；OSI 批准的 NASA 开源协议，分发需遵守协议条款；镜像保留协议文本 |
| nasa/cFS-GroundSystem | Apache-2.0 | LICENSE / main | 可镜像；保留 LICENSE 与版权声明 |
| nasa/elf2cfetbl | Apache-2.0 | LICENSE / main | 可镜像；保留 LICENSE 与版权声明 |
| nasa/gen_msgids | ⚠️ 未检测到 LICENSE 文件 | main/master 均 404 | **不可镜像**，只收录链接 |
| nasa/tblCRCTool | Apache-2.0 | LICENSE / main | 可镜像；保留 LICENSE 与版权声明 |
| nasa/tvsio | NASA-1.3（NASA Open Source Agreement v1.3） | LICENSE / master | 可镜像；OSI 批准的 NASA 开源协议，分发需遵守协议条款；镜像保留协议文本 |

- 结论：5/8 仓库许可证明确可镜像；CCDD、CTF、gen_msgids 未检测到 LICENSE 文件（已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE，main/master 分支），**不可镜像代码**，建议专区只收录官方链接；如确需镜像，先联系项目维护者获得许可
