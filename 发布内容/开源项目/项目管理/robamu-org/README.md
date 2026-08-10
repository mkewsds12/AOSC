# robamu-org · GitLink 社区镜像组织

> 来源：https://github.com/robamu-org
> 定位：在 GitLink 建立「robamu-org」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `robamu-org`（若提示已被占用，改用 `robamu-org-mirror`） |
| 组织名称 | `robamu-org（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 robamu-org 公开发布的开源项目；版权归原作者与来源组织（https://github.com/robamu-org）；仓库以只读镜像方式同步，每 8 小时更新一次。robamu-org 为德国 IRS（斯图加特大学宇航研究所）作者 Robin Mueller 的社区组织。 |
| 所在地区 | 德国 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；为组织在 GitHub 上的官方头像，是动物照片而非 Logo，属正常情况） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| TMTC Commander (tmtccmd) | [tmtccmd.md](tmtccmd.md) | Apache-2.0 | ✅ 可镜像 |
| va108xx-rs | [va108xx-rs.md](va108xx-rs.md) | Apache-2.0 / MIT 双许可 | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- **与 us-irs 同源作者**：robamu-org 与 us-irs（https://github.com/us-irs）同为德国 IRS 作者 Robin Mueller 维护的组织——us-irs 用于 IRS 研究所相关项目，robamu-org 是其个人社区组织（官方描述："Just a small organization for easier access control for some projects."）。两组织的项目作者相同、许可证风格一致（均为 Apache-2.0 / MIT 宽松许可），建议两个镜像组织建立后在组织描述中互相注明关系，便于社区用户查找同源项目。
