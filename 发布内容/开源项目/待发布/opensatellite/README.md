# opensatellite · GitLink 社区镜像组织

> 来源：https://gitee.com/opensatellite
> 定位：在 GitLink 建立该 owner 的国内社区镜像组织/账号，镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `opensatellite`（被占用则 `opensatellite-mirror`） |
| 组织名称 | `opensatellite（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 opensatellite（中国开源卫星组织 KCSA）公开发布的开源项目；版权归原作者（https://gitee.com/opensatellite）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 中国 |
| 选择头像 | 上传本文件夹 avatar.png（缺失则见备注） |
| 权限 | 默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| KS-1Q 开源立方星 | [ks-1q.md](ks-1q.md) | LGPL-2.1 | ✅ 可镜像 |
| KS-1Q（组织主页重点仓库） | [kcsa-opensatellite.md](kcsa-opensatellite.md) | LGPL-2.1 | ✅ 可镜像（与 ks-1q.md 同仓库，导入一次即可） |
| gr-kcsa-ks1q（测控 GNU Radio 模块） | [kcsa-opensatellite.md](kcsa-opensatellite.md) | ❓ 仓库无法访问（404） | ❓ 需人工核查 |

## 三、操作流程

1. 建组织 → 2. 组织内逐个「导入项目」（表单见各项目 md，注意把「拥有者」改选为本组织；KS-1Q 只导入一次）→ 3. 核对 README/LICENSE 同步 → 4. 专区后台按项目 md 标注的分类上架

## 四、合规与备注

- 非官方社区镜像，不冒充官方/作者本人，保留 LICENSE 与版权声明
- 无 LICENSE 只收链接不镜像
- 来源平台为 Gitee，仓库本就在国内平台，镜像意义主要是专区统一收录与展示；也可考虑直接联系 KCSA 邀请其入驻 GitLink
- ks-1q.md 与 kcsa-opensatellite.md 均指向 opensatellite/KS-1Q，去重后只建一个镜像项目
- gr-kcsa-ks1q 404，需人工核查后再决定
- 头像需手动从来源页获取（Gitee API 显示该组织使用默认头像 no_portrait.png，无专属头像，也可考虑用 KS-1Q 项目图片代替）

## 状态流转

- 状态：待发布（本文件夹位于 开源项目/待发布/）
- 本组织全部项目在 GitLink 建组织、镜像导入、专区上架完成后，将本文件夹移入 开源项目/已发布/
