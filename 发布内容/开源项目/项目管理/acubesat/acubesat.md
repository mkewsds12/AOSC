# AcubeSAT

> 板块：项目管理 / AcubeSAT（社区镜像）
> 来源：https://gitlab.com/acubesat
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

希腊亚里士多德大学的 3U 立方星项目，全套源码与设计开源（组织主页），涵盖星上软件与各分系统，是欧洲高校开源立方星的代表。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | 该来源为组织主页，无法整体镜像，需按下方列出的重点仓库逐个导入（每个仓库按 `仓库URL.git` 填写） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | AcubeSAT-仓库名（每个仓库一个项目） |
| 项目标识 | `acubesat`-仓库名（英文小写） |
| 项目简介 | 希腊亚里士多德大学的 3U 立方星项目，全套源码与设计开源（组织主页），涵盖星上软件与各分系统，是欧洲高校开源立方星的代表。镜像收录自 https://gitlab.com/acubesat 组织名下仓库，License：ADCS/OBC 后继仓为 MIT，COMMS 后继仓未检测到 LICENSE 文件，详见文末核查节 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 整星设计 |
| 项目语言 | 以各源仓库为准 |

## 重点仓库清单（仓库名以实际为准）

| 仓库 | URL |
|------|-----|
| OBC 相关仓库 | https://gitlab.com/acubesat/obc-software |
| COMMS 相关仓库 | https://gitlab.com/acubesat/comms-software |
| ADCS 相关仓库 | https://gitlab.com/acubesat/adcs-software |

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「整星设计」→ 保存

## 许可证核查（2026-08-10）
原列出的顶层仓库路径已不存在，组织已重组为多层子组，下表为对应后继仓库的核查结果：

| 原路径 | 后继仓库 | 结果 |
| --- | --- | --- |
| acubesat/adcs-software | acubesat/adcs/adcs-software/embedded-software | MIT（LICENSE，master） |
| acubesat/comms-software | acubesat/comms/software/comms-sw | ⚠️ 未检测到 LICENSE 文件 |
| acubesat/obc-software | acubesat/obc/cross-platform-software | MIT（LICENSE，main） |

- 结论：ADCS、OBC 后继仓许可证明确，可镜像；镜像时保留 LICENSE 与版权声明。COMMS 后继仓**不可镜像代码**，只能收录链接。镜像 URL 需按重组后的实际路径更新
