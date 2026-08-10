# KubOS

> 板块：项目管理 / kubos
> 来源：https://github.com/kubos
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

KubOS 是面向微/纳卫星的 Linux 发行版及上层软件框架，提供星载任务服务、通信与硬件抽象能力。原组织已停止维护，KubOS-Preservation-Group 有延续维护。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页（https://github.com/kubos），无法整体镜像，需按下方列出的重点仓库逐个导入（仓库名以实际为准） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `KubOS` |
| 项目标识 | `kubos` |
| 项目简介 | 面向微/纳卫星的 Linux 发行版与上层框架，提供星载任务服务、通信与硬件抽象能力；原组织已停止维护，可关注 KubOS-Preservation-Group 的延续版本。镜像收录自 https://github.com/kubos，License：各重点仓库分别核查，见文末许可证核查节 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 操作系统 |
| 项目语言 | 以源仓库为准 |

## 重点仓库列表（需逐个镜像导入，仓库名以实际为准）

| 仓库名 | URL |
|--------|-----|
| kubos（主仓库/构建框架） | https://github.com/kubos/kubos |
| kubos-linux-build（星载 Linux 构建） | https://github.com/kubos/kubos-linux-build |
| kubos-cli（开发命令行工具） | https://github.com/kubos/kubos-cli |

> 若 kubos 组织仓库已不可用，可改用延续维护组织：https://github.com/KubOS-Preservation-Group（需人工确认对应仓库）。

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「操作系统」→ 保存

## 许可证核查（2026-08-10）

| 仓库 | 结果 |
|------|------|
| kubos/kubos | ❓ 仓库无法访问（可能改名/删除/私有，GitHub 返回 404） |
| kubos/kubos-linux-build | ❓ 仓库无法访问（可能改名/删除/私有，GitHub 返回 404） |
| kubos/kubos-cli | Apache-2.0（LICENSE.txt，master 分支），可镜像 |

- 结论：kubos-cli 许可证明确，可镜像并保留 LICENSE 与版权声明；kubos、kubos-linux-build 两个仓库已不可访问，需人工核查（如改用 KubOS-Preservation-Group 的延续仓库）后再决定
