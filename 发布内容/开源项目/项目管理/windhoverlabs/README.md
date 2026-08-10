# WindhoverLabs · GitLink 社区镜像组织

> 来源：https://github.com/WindhoverLabs
> 定位：在 GitLink 建立「WindhoverLabs」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## ⚠️ 总体结论：本组织整体只能收链接

2026-08-10 核查：WindhoverLabs 旗下 5 个重点仓库（airliner、xtce_generator、auto-yamcs、yamcs-cfs、explain）**均未检测到 LICENSE 文件**（main/master 分支均已探测 LICENSE/LICENSE.md/LICENSE.txt/LICENSE-APACHE/LICENSE-MIT/COPYING/COPYRIGHT/UNLICENSE）。无许可证即默认保留所有权利，**代码一律不可镜像**。

建议二选一：

1. **只收录官方链接**：专区项目列表中登记各仓库的 GitHub 官方地址，不导入代码；
2. **联系作者或改用替代**：确需镜像的先通过 GitHub Issues/邮件联系 WindhoverLabs 维护者获得书面许可；或改用有明确许可的同类替代项目（如 NASA 官方 [cFS](https://github.com/nasa/cfs)，Apache-2.0）。

若后续与作者取得联系并获得许可，再按第三节流程执行镜像导入。

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `windhoverlabs`（若提示已被占用，改用 `windhoverlabs-mirror`） |
| 组织名称 | `WindhoverLabs（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 WindhoverLabs 公开发布的开源项目；版权归原作者与来源组织（https://github.com/WindhoverLabs）；仓库以只读镜像方式同步，每 8 小时更新一次。注意：该组织仓库暂未声明开源许可证，当前仅收录官方链接，待获得作者许可后再行镜像。 |
| 所在地区 | 美国 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| airliner（cFS 派生飞行软件栈） | [windhoverlabs.md](windhoverlabs.md) | ⚠️ 无 LICENSE | ⚠️ 无 LICENSE 只收链接 |
| xtce_generator | [windhoverlabs.md](windhoverlabs.md) | ⚠️ 无 LICENSE | ⚠️ 无 LICENSE 只收链接 |
| auto-yamcs | [windhoverlabs.md](windhoverlabs.md) | ⚠️ 无 LICENSE | ⚠️ 无 LICENSE 只收链接 |
| yamcs-cfs | [windhoverlabs.md](windhoverlabs.md) | ⚠️ 无 LICENSE | ⚠️ 无 LICENSE 只收链接 |
| explain | [windhoverlabs.md](windhoverlabs.md) | ⚠️ 无 LICENSE | ⚠️ 无 LICENSE 只收链接 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类（星务处理）

> 注：鉴于当前全部仓库无 LICENSE，第 2 步「导入项目」暂缓执行；先在专区以「收链接」方式登记官方地址，待获得许可后再导入。

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- 5 个重点仓库全部无 LICENSE，**整体只能收链接**；建议联系作者补充许可证，或改用有许可的替代项目（如 NASA cFS）
