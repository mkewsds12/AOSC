# open-space-collective · GitLink 社区镜像组织

> 来源：https://github.com/open-space-collective
> 定位：在 GitLink 建立该 owner 的国内社区镜像组织/账号，镜像其开源仓库
> 状态：待执行

## 一、新建组织填写指南（GitLink → 新建组织）

| 表单项 | 填写内容 |
|--------|---------|
| 组织账号 | `open-space-collective`（被占用则 `open-space-collective-mirror`） |
| 组织名称 | `open-space-collective（社区镜像）` |
| 组织描述 | 非官方社区镜像，仅收录 open-space-collective 公开发布的开源项目；版权归原作者（https://github.com/open-space-collective）；仓库以只读镜像方式同步，每 8 小时更新一次 |
| 所在地区 | 可留空或按项目背景填写 |
| 选择头像 | 上传本文件夹 avatar.png（缺失则见备注） |
| 权限 | 默认不勾 |

## 二、仓库镜像清单

| 仓库/项目 | 项目 md | 许可证 | 镜像可行性 |
|-----------|---------|--------|-----------|
| open-space-toolkit 系列（组织主页） | open-space-toolkit.md | Apache-2.0（flight 仓库 404 待核查） | ✅ 可镜像（flight 除外） |

## 三、操作流程

1. 建组织 → 2. 组织内逐个「导入项目」（表单见各项目 md，注意把「拥有者」改选为本组织）→ 3. 核对 README/LICENSE 同步 → 4. 专区后台按项目 md 标注的分类上架

## 四、合规与备注

- 非官方社区镜像，不冒充官方/作者本人，保留 LICENSE 与版权声明
- 无 LICENSE 只收链接不镜像
- 来源为组织主页，镜像其 open-space-toolkit 系列仓库；open-space-toolkit-flight 仓库 404（可能已删除/改名），建议人工确认后以 open-space-toolkit-data 替换
- 头像自动下载多次失败（github.com 直连超时且 API 触发限流），头像需手动从来源页获取
