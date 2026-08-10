# cfs-apps · GitLink 社区镜像组织

> 来源：https://github.com/cfs-apps
> 定位：在 GitLink 建立「cfs-apps（社区镜像）」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `cfs-apps`（若提示已被占用，改用 `cfs-apps-mirror`） |
| 组织名称 | `cfs-apps（社区镜像）` |
| 组织描述 | 本组织为非官方社区镜像，仅收录 cfs-apps 公开发布的开源项目（cFS 社区应用）；版权归原作者与来源组织（https://github.com/cfs-apps）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 美国 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| jmsg_mqtt（MQTT 消息桥） | [cfs-apps.md](cfs-apps.md) | GPL-3.0（含附加条款） | ✅ 可镜像 |
| mqtt_lib | [cfs-apps.md](cfs-apps.md) | GPL-3.0（含附加条款） | ✅ 可镜像 |
| pi_iolib（树莓派 IO） | [cfs-apps.md](cfs-apps.md) | GPL-3.0（含附加条款） | ✅ 可镜像 |
| pl_sim（载荷模拟） | [cfs-apps.md](cfs-apps.md) | GPL-3.0（含附加条款） | ✅ 可镜像 |
| bc42_ctrl（42 姿控接入 cFS） | [cfs-apps.md](cfs-apps.md) | AGPL-3.0 | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- 5 仓库均为 GPL/AGPL 系（4 个 GPL-3.0 含附加条款 + 1 个 AGPL-3.0），衍生/分发（AGPL 含网络提供服务）均需开源同等授权；镜像只读展示合规
- 注意：cfs-basecamp 属于 cfs-tools 组织（https://github.com/cfs-tools），不在本组织，不在此迁移
