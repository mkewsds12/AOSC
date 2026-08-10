# spacelab-ufsc（巴西 UFSC 太空实验室） · GitLink 社区镜像组织

> 来源：https://github.com/spacelab-ufsc
> 定位：在 GitLink 建立「spacelab-ufsc」的国内社区镜像组织，批量镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `spacelab-ufsc`（若提示已被占用，改用 `spacelab-ufsc-mirror`） |
| 组织名称 | `spacelab-ufsc（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 spacelab-ufsc（巴西 UFSC 太空实验室）公开发布的开源项目；版权归原作者与来源组织（https://github.com/spacelab-ufsc）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 巴西 |
| 选择头像 | 上传本文件夹 `avatar.png`（官方头像，仅供辨识；如缺失见备注） |
| 权限 | 「项目管理员可以添加或移除团队的访问权限」按需勾选，默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| spacelab-ufsc（组织主页，含 obdh2/eps2/ttc2） | [spacelab-ufsc.md](spacelab-ufsc.md) | obdh2/eps2/ttc2 均未检测到 LICENSE 文件（2026-08-10 核查） | ⚠️ 无 LICENSE 只收链接 |

## 三、操作流程

1. 按第一节创建组织
2. 组织内逐个「导入项目」：各项目 md 中有完整的导入表单填写指南（URL / 项目标识 / 简介 / 勾选镜像）——注意本组织 3 个重点仓库均无 LICENSE，跳过镜像导入，只在专区收录官方链接
3. 导入完成后核对 README / LICENSE 同步正常
4. 专区管理后台 → 项目管理 → 添加项目 → 挂到项目 md 中标注的分类

## 四、合规与备注

- 本组织为**非官方社区镜像**：不冒充官方、不修改上游内容、保留各仓库 LICENSE 与版权声明
- 无 LICENSE 的仓库只收录官方链接，不镜像代码；确需镜像先联系项目维护者获得许可
- obdh2/eps2/ttc2 均无 LICENSE，只能收链接；建议联系实验室（https://spacelab.ufsc.br）或等待上游补许可证后再行镜像
