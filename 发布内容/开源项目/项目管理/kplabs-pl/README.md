# KP Labs · GitLink 社区镜像组织

> 来源：https://github.com/kplabs-pl
> 定位：在 GitLink 建立「KP Labs」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `kplabs-pl`（若提示已被占用，改用 `kplabs-pl-mirror`） |
| 组织名称 | `KP Labs（社区镜像）` |
| 组织描述 | KP Labs（波兰，星载智能与在轨数据处理）开源项目的非官方社区镜像，仅收录 KP Labs 公开发布的开源项目；版权归原作者与来源组织（https://github.com/kplabs-pl）；仓库以只读镜像方式同步，每 8 小时更新一次。 |
| 所在地区 | 波兰 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| OPS-SAT-AD | [ops-sat-ad.md](ops-sat-ad.md) | MIT（LICENSE，main 分支） | ✅ 可镜像 |
| KP Labs AI-datasets | [ai-datasets.md](ai-datasets.md) | 未检测到 LICENSE 文件 | ⚠️ 无 LICENSE 只收链接 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- OPS-SAT-AD 为 MIT，可直接镜像；AI-datasets 无 LICENSE，只能收链接（见 [ai-datasets.md](ai-datasets.md) 许可证核查节）
- 头像备注：本机直连 github.com 超时，`avatar.png` 实际取自 GitHub CDN（avatars.githubusercontent.com/u/47846042），与 https://github.com/kplabs-pl.png 为同一官方头像
