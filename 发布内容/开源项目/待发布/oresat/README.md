# oresat · GitLink 社区镜像组织

> 来源：https://github.com/oresat
> 定位：在 GitLink 建立该 owner 的国内社区镜像组织/账号，镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `oresat`（被占用则 `oresat-mirror`） |
| 组织名称 | `oresat（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 oresat 公开发布的开源项目；版权归原作者（https://github.com/oresat）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 美国（波特兰州立大学，可留空） |
| 选择头像 | 上传本文件夹 avatar.png（缺失则见备注） |
| 权限 | 默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| oresat-firmware | [oresat.md](oresat.md) | GPL-3.0 | ✅ 可镜像 |
| oresat-configs | [oresat.md](oresat.md) | GPL-3.0 | ✅ 可镜像 |
| oresat-dxwifi | [oresat.md](oresat.md) | GPL-3.0 | ✅ 可镜像 |
| oresat-structure | [oresat.md](oresat.md) | ⚠️ 未检测到 LICENSE | ⚠️ 无 LICENSE 只收链接 |

## 三、操作流程

1. 建组织 → 2. 组织内逐个「导入项目」（表单见项目 md 的重点仓库清单，注意把「拥有者」改选为本组织）→ 3. 核对 README/LICENSE 同步 → 4. 专区后台按项目 md 标注的分类上架

## 四、合规与备注

- 非官方社区镜像，不冒充官方/作者本人，保留 LICENSE 与版权声明
- 无 LICENSE 只收链接不镜像
- 来源为组织主页，需按项目 md 中「重点仓库清单」逐个导入；oresat-structure 无 LICENSE 只收链接

## 状态流转

- 状态：待发布（本文件夹位于 开源项目/待发布/）
- 本组织全部项目在 GitLink 建组织、镜像导入、专区上架完成后，将本文件夹移入 开源项目/已发布/
