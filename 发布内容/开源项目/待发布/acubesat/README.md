# AcubeSAT 亚里士多德大学 · GitLink 社区镜像组织

> 来源：<https://gitlab.com/acubesat>（另有 GitHub <https://github.com/AcubeSAT>）
> 定位：在 GitLink 建立「AcubeSAT」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
| :--- | :--- |
| 组织账号 | `acubesat`（若提示已被占用，改用 `acubesat-mirror`） |
| 组织名称 | `AcubeSAT（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 AcubeSAT（希腊亚里士多德大学 SpaceDot 团队 3U 立方星项目）公开发布的开源项目；版权归原作者与来源组织（<https://gitlab.com/acubesat>）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 希腊 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
| :--- | :--- | :--- | :--- |
| acubesat/adcs/adcs-software/embedded-software（ADCS 后继仓） | [acubesat.md](acubesat.md) | MIT（LICENSE，master） | ✅ 可镜像 |
| acubesat/obc/cross-platform-software（OBC 后继仓） | [acubesat.md](acubesat.md) | MIT（LICENSE，main） | ✅ 可镜像 |
| acubesat/comms/software/comms-sw（COMMS 后继仓） | [acubesat.md](acubesat.md) | ⚠️ 未检测到 LICENSE 文件 | ⚠️ 无 LICENSE 只收链接 |
| AcubeSAT/ecss-services（GitHub） | [ecss-services.md](ecss-services.md) | MIT（LICENSE，master） | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- GitHub 的 ADCS/OBC 后继仓为 MIT，可镜像；comms-sw 无 LICENSE，只收录链接
- GitLab 组织主页结构近期重组过，原顶层仓库路径已不存在，镜像 URL 需按重组后的实际子组路径（见 acubesat.md 许可证核查节）填写
- 项目同时托管在 GitLab（gitlab.com/acubesat）与 GitHub（github.com/AcubeSAT），同名仓库镜像前确认内容一致，避免重复收录

## 状态流转

- 状态：待发布（本文件夹位于 开源项目/待发布/）
- 本组织全部项目在 GitLink 建组织、镜像导入、专区上架完成后，将本文件夹移入 开源项目/已发布/
