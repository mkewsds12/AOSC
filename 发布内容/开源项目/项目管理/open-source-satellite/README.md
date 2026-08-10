# Open-Source-Satellite · GitLink 社区镜像组织

> 来源：https://github.com/Open-Source-Satellite
> 定位：在 GitLink 建立 Open-Source-Satellite 的国内社区镜像组织/账号，镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `open-source-satellite`（被占用则 `open-source-satellite-mirror`） |
| 组织名称 | `Open-Source-Satellite（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 Open-Source-Satellite 公开发布的开源项目；版权归原作者（https://github.com/Open-Source-Satellite）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 可留空 |
| 选择头像 | 上传本文件夹 avatar.png（缺失则见备注） |
| 权限 | 默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| Mercury-GS（独立项目条目） | [mercury-gs.md](mercury-gs.md) | 自定义/专有许可（外链条款） | ❓ 需人工核查 |
| Mercury-GS（组织主页条目，整星设计板块） | [open-source-satellite.md](open-source-satellite.md) | ❓ 同上自定义许可 | ❓ 需人工核查（与 mercury-gs.md 同仓库，核查清楚前只收链接） |
| Open-Source-Satellite 组织（组织主页收录，逐个仓库核查） | [open-source-satellite.md](open-source-satellite.md) | 自定义许可（各仓库分别核查） | ❓ 需人工核查 |

## 三、操作流程

1. 建组织 → 2. 组织内逐个「导入项目」（表单见各项目 md，注意把「拥有者」改选为本组织）→ 3. 核对 README/LICENSE 同步 → 4. 专区后台按项目 md 标注的分类上架

## 四、合规与备注

- 非官方社区镜像，不冒充官方/作者本人，保留 LICENSE 与版权声明
- 无 LICENSE 只收链接不镜像
- **Mercury-GS 的 LICENSE.md 仅指向外部条款**（www.kispe.co.uk/projectlicenses/RA2001001003），为自定义/专有许可，未授予明确开源权利；在人工确认授权前**不镜像代码**，专区可先只收录官方链接
