# AeroRust · GitLink 社区镜像组织

> 来源：<https://github.com/AeroRust>
> 定位：在 GitLink 建立该 owner 的国内社区镜像组织/账号，镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
| :--- | :--- |
| 组织账号 | `aerorust`（被占用则 `aerorust-mirror`） |
| 组织名称 | `AeroRust（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 AeroRust 公开发布的开源项目；版权归原作者（<https://github.com/AeroRust>）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 可留空或按项目背景填写 |
| 选择头像 | 上传本文件夹 avatar.png（缺失则见备注） |
| 权限 | 默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
| :--- | :--- | :--- | :--- |
| AeroRust 组织（adcs / navigation / astrodynamics） | aerorust.md | ❓ 三个重点仓库均 404 | ❓ 需人工核查 |
| nanosat-workshop | nanosat-workshop.md | Apache-2.0 / MIT 双许可 | ✅ 可镜像 |
| splice | splice.md | GPL-3.0 | ✅ 可镜像 |

## 三、操作流程

1. 建组织 → 2. 组织内逐个「导入项目」（表单见各项目 md，注意把「拥有者」改选为本组织）→ 3. 核对 README/LICENSE 同步 → 4. 专区后台按项目 md 标注的分类上架

## 四、合规与备注

- 非官方社区镜像，不冒充官方/作者本人，保留 LICENSE 与版权声明
- 无 LICENSE 只收链接不镜像
- 来源是组织主页（无具体仓库名）；aerorust.md 中所列三个重点仓库（adcs/navigation/astrodynamics）当前均无法访问（404，可能改名/删除/私有），需人工登录 <https://github.com/AeroRust> 核对实际仓库清单并逐个核查许可证，未确认前不得镜像任何代码
- splice 为 GPL-3.0：衍生/分发需开源同等授权；镜像只读展示合规

## 状态流转

- 状态：待发布（本文件夹位于 开源项目/待发布/）
- 本组织全部项目在 GitLink 建组织、镜像导入、专区上架完成后，将本文件夹移入 开源项目/已发布/
