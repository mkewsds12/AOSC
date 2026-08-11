# ESA 欧洲航天局 · GitLink 社区镜像组织

> 来源：<https://github.com/esa>
> 定位：在 GitLink 建立「ESA（社区镜像）」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
| :--- | :--- |
| 组织账号 | `esa`（若提示已被占用，改用 `esa-mirror`） |
| 组织名称 | `ESA（社区镜像）` |
| 组织描述 | 非官方社区镜像组织，仅收录 ESA 欧洲航天局公开发布的开源项目；版权归原作者与来源组织（<https://github.com/esa>）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 欧洲 / 法国巴黎 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
| :--- | :--- | :--- | :--- |
| nanosat-mo-framework | [nanosat-mo-framework.md](nanosat-mo-framework.md) | ⚠️ 未检测到 LICENSE 文件 | ⚠️ 无 LICENSE 只收链接 |
| esa-mo-services（mo-services-java 等 5 个仓库） | [esa-mo-services.md](esa-mo-services.md) | 仅 mo.viewer.web 为 MIT，其余 4 仓库未检测到 LICENSE | ⚠️ 无 LICENSE 只收链接（mo.viewer.web ✅ 可镜像） |
| nmf-mission-ops-sat | [nmf-mission-ops-sat.md](nmf-mission-ops-sat.md) | ⚠️ 未检测到 LICENSE 文件 | ⚠️ 无 LICENSE 只收链接 |
| esa-gitlab（GitLab 组织入口） | [esa-gitlab.md](esa-gitlab.md) | 入口可收录链接；重点仓库 the_opssat_case_starter_kit 未检测到 LICENSE | ⚠️ 无 LICENSE 只收链接 |
| pykep | [pykep.md](pykep.md) | MPL-2.0 | ✅ 可镜像 |
| dsgp4 | [dsgp4.md](dsgp4.md) | GPL-3.0 | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- ESA 有 GitHub 与 GitLab 两个官方组织：GitHub（<https://github.com/esa>）与 GitLab（<https://gitlab.com/EuropeanSpaceAgency>）。可分别建两个镜像组织（如 `esa` 与 `esa-gitlab`），也可在本组织下合并收录两个来源的仓库，建组织时按需决策
- nanosat-mo-framework 与 esa-mo-services 系列仓库大部分未检测到 LICENSE 文件，原则上只收录官方链接；esa-mo-services 中仅 mo.viewer.web（MIT）可直接镜像

## 状态流转

- 状态：待发布（本文件夹位于 开源项目/待发布/）
- 本组织全部项目在 GitLink 建组织、镜像导入、专区上架完成后，将本文件夹移入 开源项目/已发布/
