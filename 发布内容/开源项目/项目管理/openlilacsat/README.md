# openlilacsat · GitLink 社区镜像组织

> 来源：https://gitee.com/openlilacsat
> 定位：在 GitLink 建立该 owner 的国内社区镜像组织/账号，镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `openlilacsat`（被占用则 `openlilacsat-mirror`） |
| 组织名称 | `openlilacsat（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 openlilacsat（哈尔滨工业大学紫丁香学生微纳卫星团队）公开发布的开源项目；版权归原作者（https://gitee.com/openlilacsat）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 中国 |
| 选择头像 | 上传本文件夹 avatar.png（缺失则见备注） |
| 权限 | 默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| ASRTU-1_OBC_Software（ASRTU-1 星务软件，星务处理板块） | [asrtu-1.md](asrtu-1.md) | GPL-2.0 | ✅ 可镜像 |
| ASRTU-1_OBC_Software（整星设计板块收录） | [openlilacsat.md](openlilacsat.md) | GPL-2.0 | ✅ 可镜像 |
| 组织其余仓库 | [openlilacsat.md](openlilacsat.md) | 需在组织主页逐个核对 | ❓ 需人工核查 |

## 三、操作流程

1. 建组织 → 2. 组织内逐个「导入项目」（先到 https://gitee.com/openlilacsat 核对当前公开仓库列表，表单见项目 md，注意把「拥有者」改选为本组织）→ 3. 核对 README/LICENSE 同步 → 4. 专区后台按项目 md 标注的分类上架

## 四、合规与备注

- 非官方社区镜像，不冒充官方/作者本人，保留 LICENSE 与版权声明
- 无 LICENSE 只收链接不镜像
- 来源平台为 Gitee，仓库本就在国内平台，镜像意义主要是专区统一收录与展示；也可考虑直接联系紫丁香团队邀请其入驻 GitLink
- 组织后续公开的仓库需逐个核查许可证后再镜像
- 头像需手动从来源页获取（Gitee 组织无公开 API 头像地址，https://gitee.com/openlilacsat）
- asrtu-1.md 与 openlilacsat.md 均收录 ASRTU-1_OBC_Software（分属星务处理/整星设计板块），导入时只建一个镜像仓库，上架时可按板块需要挂载，避免重复导入
