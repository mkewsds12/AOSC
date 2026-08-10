# NASA（社区镜像） · GitLink 社区镜像组织

> 来源：https://github.com/nasa
> 定位：在 GitLink 建立「NASA（社区镜像）」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `nasa`（若提示已被占用，改用 `nasa-mirror`） |
| 组织名称 | `NASA（社区镜像）` |
| 组织描述 | 本组织为非官方社区镜像，仅收录 NASA 公开发布的开源项目；版权归原作者与来源组织（https://github.com/nasa）；仓库以只读镜像方式同步，每 8 小时更新一次，方便国内用户访问 NASA 航天开源软件（cFS/F'、OpenMCT、NOS3 等）。 |
| 所在地区 | 美国 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| NASA cFE（核心飞行执行环境） | [cfe.md](cfe.md) | Apache-2.0 | ✅ 可镜像 |
| NASA cFS（核心飞行系统） | [cfs.md](cfs.md) | Apache-2.0 | ✅ 可镜像 |
| NASA F'（F Prime） | [fprime.md](fprime.md) | Apache-2.0 | ✅ 可镜像 |
| NASA cFS 工具生态（8 仓库） | [cfs-tools.md](cfs-tools.md) | 混合：Apache-2.0 ×4、NOSA-1.3 ×2、无 LICENSE ×3（CCDD/CTF/gen_msgids） | ⚠️ 无 LICENSE 的 CCDD/CTF/gen_msgids 只收链接；其余 5 个可镜像 |
| NASA OSAL（操作系统抽象层） | [osal.md](osal.md) | Apache-2.0 | ✅ 可镜像 |
| NASA spacewasm | [spacewasm.md](spacewasm.md) | Apache-2.0 | ✅ 可镜像 |
| NASA CryptoLib | [cryptolib.md](cryptolib.md) | NOSA-1.3（NASA Open Source Agreement v1.3） | ✅ 可镜像 |
| NASA NOS3（卫星操作仿真器） | [nos3.md](nos3.md) | NOSA-1.3 | ✅ 可镜像 |
| NASA OpenMCT（遥测可视化） | [openmct.md](openmct.md) | Apache-2.0 | ✅ 可镜像 |
| GMSEC_API（地面站中间件） | [gmsec-api.md](gmsec-api.md) | NOSA-1.3（仓库根目录 NOSA.pdf） | ✅ 可镜像 |
| NASA hermes | [nasa-hermes.md](nasa-hermes.md) | Apache-2.0 | ✅ 可镜像 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- NASA 部分项目许可证为 NOSA-1.3（NASA Open Source Agreement v1.3，OSI 批准但与 GPL 不兼容）：衍生作品分发需开源并保留协议文本；镜像为只读展示，合规，镜像时保留 LICENSE / NOSA.pdf 与版权声明
- cfs-tools.md 涉及 8 个仓库：其中 CCDD、CTF、gen_msgids 未检测到 LICENSE 文件，**不可镜像代码**，专区只收录官方链接；其余 5 个仓库（SIL、tvsio、cFS-GroundSystem、elf2cfetbl、tblCRCTool）可镜像
- 头像说明：`avatar.png` 为 NASA 官方 GitHub 组织头像（因 github.com 直连超时，实际经 `avatars.githubusercontent.com/u/848102` 获取，已人工确认为 NASA 官方 Logo）
