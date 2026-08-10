# 项目管理 · 组织镜像总览

> 用途：在 GitLink 上按「来源组织 → 镜像组织 → 旗下项目」的方式批量收录国外开源航天项目
> 工作流：**建镜像组织 → 组织内逐个镜像导入仓库 → 挂到专区分类**
> 数据基础：《调研/开源项目调研.md》、2026-08-10 许可证核查（结果在各项目 md 末尾）

---

## 一、目录结构

每个来源组织一个文件夹：

```
项目管理/
├── README.md            # 本文件
├── nasa/                # 组织文件夹（GitLink 组织账号建议名）
│   ├── README.md        # 新建组织填写指南 + 仓库镜像清单 + 流程 + 合规备注
│   ├── avatar.png       # 官方组织头像（建组织时上传）
│   └── *.md             # 该组织旗下各项目的导入指南（含许可证核查）
├── esa/
└── ...
```

## 二、已整理组织清单（20 个）

| 组织文件夹 | 来源 | 仓库数(已建档) | 许可证情况 | 优先级建议 |
|-----------|------|--------------|-----------|-----------|
| openspacecode | github.com/OpenSpaceCode | 7 | 全部 Apache-2.0 | ★ 首批（全许可，直接整组织镜像） |
| n7space | github.com/n7space | 2 | Apache-2.0/MIT、GPL-3.0 | ★ 首批 |
| us-irs | github.com/us-irs | 2 | 全部 Apache-2.0 | ★ 首批（注意 sat-rs 勿与 sds3 重复） |
| robamu-org | github.com/robamu-org | 2 | Apache-2.0/MIT | ★ 首批 |
| cfs-apps | github.com/cfs-apps | 5 | GPL/AGPL 系 | ★ 首批 |
| birdsopensource | github.com/BIRDSOpenSource | 2 | MIT | ★ 首批 |
| spel-uchile | github.com/spel-uchile | 4 | GPL/LGPL 系 | 第二批 |
| nyx-space | github.com/nyx-space | 2 | MPL-2.0、AGPL-3.0 | 第二批（nyx 已迁 GitLab 新地址） |
| nasa | github.com/nasa | 11 | Apache-2.0/NOSA-1.3 为主，3 仓无 LICENSE | 第二批 |
| nasa-ammos | github.com/NASA-AMMOS | 9 | MIT/Apache-2.0，AIT-GUI 待确认 | 第二批 |
| acubesat | gitlab.com/acubesat | 4 | MIT×3，comms-sw 无 LICENSE | 第二批 |
| kplabs-pl | github.com/kplabs-pl | 2 | OPS-SAT-AD MIT，AI-datasets 无 LICENSE | 第二批 |
| librespacefoundation | gitlab.com/librespacefoundation | 10+ | GPL/AGPL/LGPL 为主，个别无 LICENSE，GitLab 已重组 | 第二批（先核对重组后路径） |
| esa | github.com/esa | 6 | pykep/dSGP4 可镜像，MO 系列多无 LICENSE | 第三批 |
| pw-sat2 | github.com/PW-Sat2 | 2 | PWSat2OBC AGPL-3.0，3 仓 404 | 第三批 |
| delfispace | github.com/DelfiSpace | 63（建档 7） | DelfiTLM 无 LICENSE，6 仓 404 | 第三批（先核对现有仓库清单） |
| nasa-jpl | github.com/nasa-jpl | 1 | ION-DTN 无 LICENSE | 仅收链接 |
| windhoverlabs | github.com/WindhoverLabs | 5 | 全部无 LICENSE | 仅收链接（建议联系作者） |
| spacelab-ufsc | github.com/spacelab-ufsc | 3 | 全部无 LICENSE | 仅收链接（建议联系实验室） |
| yamcs | github.com/yamcs | 1 | 无 LICENSE | 仅收链接（测运控招牌，建议优先联系官方入驻） |

## 三、标准操作流程

1. **建组织**：按组织文件夹 README 第一节填「新建组织」表单（账号 / 名称带"社区镜像" / 描述含非官方声明 / 上传 avatar.png）
2. **镜像导入**：组织内逐个「导入项目」，表单填写见各项目 md；无 LICENSE 的项目跳过导入、只在专区收官方链接
3. **核对同步**：检查 README / LICENSE 是否同步正常
4. **挂专区**：专区后台 → 项目管理 → 添加项目 → 按项目 md 标注的分类上架
5. **宣传**：重要项目上新时在「新闻资讯/项目速递」发一篇（见《航天专区_资讯维护指南》）

## 四、合规红线（全组织通用）

- 组织名称与描述必须注明**非官方社区镜像**，不冒充官方
- 镜像仓库只读、不修改上游内容、保留 LICENSE 与版权声明
- 无 LICENSE = 无授权：只收链接不镜像；确需镜像先取得维护者许可
- GitLab 重组 / 仓库 404 的组织，导入前先核对实际仓库路径

## 五、全量组织化完成情况（2026-08-10 更新）

调研的 235 个项目 md 已**全部**按「owner → 项目」归入本目录，共 **182 个文件夹**：

- 20 个大组织文件夹（见第二节）
- 161 个中小组织/个人 owner 文件夹（单仓库个人账号也按同样结构建档，README 内容相应精简）
- 1 个 `生态入口/` 文件夹：topic 聚合页、在线服务官网、未公开项目（cansat、ccsds 汇总、OpenStarTracker、nova.astrometry、EGS-CC 等），不建镜像组织，仅作收录线索

`发布内容/**/待发布/` 下的项目 md 已全部迁出（新闻资讯不属于本项目流，未动）。

**头像情况**：约 165 个文件夹已下载官方头像（avatar.png，经验证）；十余个未下载的（Gitee 组织用系统默认头像、Bitbucket/SourceForge/自建 GitLab 无直链、个别 GitHub 限流失败）已在各自 README 备注「头像需手动从来源页获取」，建组织时手动上传即可。

**许可证总账**（按 2026-08-10 核查）：

- ✅ 许可证明确可镜像：约 190 个 md（Apache/MIT/BSD/MPL/ISC/EPL/CC0 等宽松许可 + GPL/LGPL/AGPL 系，后者已附 copyleft 义务提醒）
- ⚠️ 无 LICENSE 只收链接：约 30 个 md（README 清单中已标 ⚠️，建组织时可建但暂不导入代码）
- ❓ 需人工核查：约 15 个 md（自定义许可、仓库 404、平台限制等，逐条见各 README 备注）
