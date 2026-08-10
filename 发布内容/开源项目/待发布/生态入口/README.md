# 生态入口 · 收录线索与在线服务汇总

> 定位：汇总不适合建立 GitLink 镜像组织的来源——GitHub topic 聚合页、独立官网/在线服务、未公开项目等
> 状态：仅作收录线索保留，不建组织、不镜像、不下头像

本文件夹下的条目**都不是可直接镜像的 git 仓库来源**，统一不建 owner 镜像组织。各条目按下方处置建议执行：从入口页筛出的具体仓库，须回到「按 owner 建镜像组织」的标准流程逐个处理。

## 条目清单与处置建议

| 文件 | 来源类型 | 处置建议 |
| :--- | :--- | :--- |
| [github-topic-cubesat.md](github-topic-cubesat.md) | GitHub topic 聚合页（cubesat 等主题入口） | 不镜像本页；定期人工浏览主题页，筛出星标高、维护活跃的具体仓库，逐个核查许可证后按标准流程建 owner 组织镜像 |
| [cansat.md](cansat.md) | GitHub topic 聚合页（cansat 主题，167+ 仓库） | 同上；可优先筛选 CatSat、POA-OBC、OSA 等文档全的项目逐个核查后收录 |
| [ccsds-标准库汇总.md](ccsds-标准库汇总.md) | GitHub topic 聚合页（ccsds 主题） | 不镜像本页；表中重点仓库（CCSDSPy、ccsds-spacepacket 等）逐个核查 LICENSE 后按标准流程收录，上架「测控通信」分类 |
| [nova-astrometry.md](nova-astrometry.md) | 在线服务（nova.astrometry.net 星图识别） | 服务本身只收链接不镜像；如需镜像其源码 astrometry.net，先人工确认官方 git 仓库地址并单独核查许可证 |
| [openstartracker.md](openstartracker.md) | 独立官网（openstartracker.org） | 官网只收链接不镜像；对应开源代码需人工确认 git 仓库地址并核查许可证后再决定 |
| [egs-cc.md](egs-cc.md) | 无公开 URL（ESA 会员制 GitLab，未公开） | 暂不可收录：代码仅限 ESA 会员机构访问，不建镜像组织；保留为跟踪线索，若未来公开发布再按标准流程处理 |
| [egs-cc.md](egs-cc.md) | 无公开 URL（ESA 会员制 GitLab，代码未公开，仅限会员机构访问） | 暂不可收录：不镜像、不上架；持续跟踪 EGS-CC 开源进展，一旦公开发布再按来源 owner 走标准流程建组织镜像 |

## 通用规则

- 本文件夹条目一律不建 GitLink 组织、不做镜像导入、不上架专区（筛出的具体仓库除外）
- 从入口页/官网发现的每一个具体仓库：先确认 git 地址 → 核查 LICENSE（无 LICENSE 只收链接）→ 按 owner 建立/归入镜像组织 → 导入并上架
- 后续批次如有同类型条目（topic 页、在线服务、无公开仓库的来源），继续移入本文件夹并补充到上表
