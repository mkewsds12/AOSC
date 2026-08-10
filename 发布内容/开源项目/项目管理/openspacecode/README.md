# OpenSpaceCode（社区镜像） · GitLink 社区镜像组织

> 来源：https://github.com/OpenSpaceCode
> 定位：在 GitLink 建立「OpenSpaceCode（社区镜像）」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `openspacecode`（若提示已被占用，改用 `openspacecode-mirror`） |
| 组织名称 | `OpenSpaceCode（社区镜像）` |
| 组织描述 | 本组织为非官方社区镜像，仅收录 OpenSpaceCode 公开发布的开源项目（极简嵌入式 CCSDS/ECSS 协议 C 实现）；版权归原作者与来源组织（https://github.com/OpenSpaceCode）；仓库以只读镜像方式同步，每 8 小时更新一次。 |
| 所在地区 | 欧洲 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| EmbeddedPUS | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |
| EmbeddedSpacePacket | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |
| EmbeddedSDLP | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |
| EmbeddedCFDP | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |
| EmbeddedSpaceWire | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |
| EmbeddedCUCTime | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |
| OpenSpaceEGSE | [openspacecode.md](openspacecode.md) | Apache-2.0 | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类（测控通信）

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- 7 个仓库全部 Apache-2.0，是本批来源组织中最适合整体镜像的组织之一，建议作为**首批推荐**优先执行
- 头像说明：`avatar.png` 为 OpenSpaceCode GitHub 组织官方头像（经 api.github.com 获取头像地址后下载验证）；本机网络无法直连 github.com，如后续更新头像可从 https://github.com/OpenSpaceCode 手动获取
