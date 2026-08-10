# NASA AMMOS（社区镜像） · GitLink 社区镜像组织

> 来源：https://github.com/NASA-AMMOS
> 定位：在 GitLink 建立「NASA AMMOS（社区镜像）」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `nasa-ammos`（若提示已被占用，改用 `nasa-ammos-mirror`） |
| 组织名称 | `NASA AMMOS（社区镜像）` |
| 组织描述 | NASA AMMOS（Advanced Multi-Mission Operations System，NASA JPL 多任务地面系统开源组织）非官方社区镜像，仅收录 NASA-AMMOS 公开发布的开源项目；版权归原作者与来源组织（https://github.com/NASA-AMMOS）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 美国 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| AMMOS PlanDev | [ammos-plandev.md](ammos-plandev.md) | MIT | ✅ 可镜像 |
| AIT-Core | [nasa-ammos.md](nasa-ammos.md) | MIT | ✅ 可镜像 |
| AIT-GUI | [nasa-ammos.md](nasa-ammos.md) | ❓ 仓库无法访问 | ❓ 需人工核查 |
| AIT-CFS | [nasa-ammos.md](nasa-ammos.md) | MIT | ✅ 可镜像 |
| AIT-DSN | [nasa-ammos.md](nasa-ammos.md) | MIT | ✅ 可镜像 |
| MMTC | [nasa-ammos.md](nasa-ammos.md) | Apache-2.0 | ✅ 可镜像 |
| MMGIS | [nasa-ammos.md](nasa-ammos.md) | Apache-2.0 | ✅ 可镜像 |
| landscape | [nasa-ammos.md](nasa-ammos.md) / [ammos-landscape.md](ammos-landscape.md) | Apache-2.0 | ✅ 可镜像 |
| AMMOS Landscape | [ammos-landscape.md](ammos-landscape.md) | Apache-2.0 | ✅ 可镜像 |

（landscape 仓库同时出现在组织级清单与独立项目 md 中，导入一次即可，专区上架时分别挂「地面测试」与「学习资料」分类。）

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）；NASA-AMMOS 组织主页无法整体镜像，按 nasa-ammos.md 中的重点仓库表逐个导入
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类（AMMOS Landscape 走资源管理后台「学习资料」领域上架）

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- AIT-GUI 仓库无法访问（README 在 main/master 均 404，可能改名/删除/私有），需人工确认仓库状态后再决定是否导入
- nasa-ammos.md 为组织级清单文件，许可证核查按仓库逐个记录，导入时以其中「许可证核查」表为准
