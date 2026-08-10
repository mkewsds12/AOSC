# Libre Space Foundation · GitLink 社区镜像组织

> 来源：https://gitlab.com/librespacefoundation
> 定位：在 GitLink 建立「Libre Space Foundation」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `librespacefoundation`（若提示已被占用，改用 `librespacefoundation-mirror`） |
| 组织名称 | `Libre Space Foundation（社区镜像）` |
| 组织描述 | Libre Space Foundation（LSF，希腊）开源航天项目的非官方社区镜像，仅收录其公开发布的开源项目（UPSat、SatNOGS 等）；版权归原作者与来源组织（https://gitlab.com/librespacefoundation）；仓库以只读镜像方式同步，每 8 小时更新一次。 |
| 所在地区 | 希腊 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| UPSat | [upsat.md](upsat.md) | GPL-3.0 | ✅ 可镜像 |
| cronos-rocket | [cronos-rocket.md](cronos-rocket.md) | GPL-3.0 | ✅ 可镜像 |
| Libre Space Foundation（组织主页/子组汇总） | [libre-space-foundation.md](libre-space-foundation.md) | 混合：GPL-3.0 / AGPL-3.0 / LGPL-3.0；phasma、libresat-i ⚠️ 无 LICENSE | ⚠️ 有 LICENSE 仓库可镜像；phasma / libresat-i 无 LICENSE 只收链接 |
| SatNOGS | [satnogs.md](satnogs.md) | AGPL-3.0（各组件） | ✅ 可镜像 |
| 亥姆霍兹线圈（helmholtz-coils-hw） | [helmholtz-coils-hw.md](helmholtz-coils-hw.md) | CERN-OHL-1.2（开源硬件） | ✅ 可镜像 |
| SatNOGS COMMS | [satnogs-comms.md](satnogs-comms.md) | ❓ 仓库 404，无法探测 LICENSE | ❓ 需人工核查 |
| gr-satnogs | [gr-satnogs.md](gr-satnogs.md) | GPL-3.0 | ✅ 可镜像 |
| gr-leo | [gr-leo.md](gr-leo.md) | GPL-3.0 | ✅ 可镜像 |
| OSDLP | [osdlp.md](osdlp.md) | GPL-3.0 | ✅ 可镜像 |
| awesome-open-space | [awesome-open-space.md](awesome-open-space.md) | ⚠️ 未检测到 LICENSE | ⚠️ 无 LICENSE 只收链接 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- LSF 近期重组了 GitLab 仓库结构：upsat、satnogs、cronos-rocket 等已迁为子组（如 `librespacefoundation/upsat/upsat-obc-software`），各项目 md 头部的来源 URL 多为重组前的旧路径，**填写镜像 URL 时务必以重组后的实际仓库路径为准**（各 md 的「许可证核查」节已注明代表仓库的实际路径）
- phasma、libresat-i 两个项目无 LICENSE，按无 LICENSE 规则只收链接
- SatNOGS 组件（satnogs-client / satnogs-db / satnogs-auto-scheduler / satnogs-decoders 等）均为 AGPL-3.0：衍生/分发及通过网络提供服务均需开源同等授权，只读镜像展示合规
- satnogs-comms 仓库当前 404（可能已删除/改名/设为私有），镜像前需人工核查其实际去向
