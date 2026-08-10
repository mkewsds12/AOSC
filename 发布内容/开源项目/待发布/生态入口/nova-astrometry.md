# nova.astrometry.net

> ⚠️ 非 git 仓库地址，不能直接镜像导入
> 板块：项目管理 / 生态入口
> 来源：http://nova.astrometry.net/
> 状态：待发布（建组织 → 镜像导入 → 专区上架）

## 项目简介

nova.astrometry.net 是在线星图识别服务，上传星空图像即可解算视场指向，可用于验证星敏感器算法输出。其背后是开源的 astrometry.net 星图识别引擎。镜像收录自 http://nova.astrometry.net/ ，License 以源仓库 LICENSE 为准。

## GitLink 导入填写指南（镜像方式）

| 表单项 | 填写内容 |
|--------|---------|
| 导入仓库URL | ⚠️ 该来源为在线服务，非 git 仓库地址。可参考的源码仓库为 astrometry.net（需人工确认其官方仓库地址后加 `.git` 导入） |
| 导入私有项目 | 不勾选（源仓库为公开项目） |
| 拥有者 | `sds3`（下拉里没有则需先加入组织） |
| 项目名称 | `nova.astrometry.net` |
| 项目标识 | `nova-astrometry` |
| 项目简介 | 在线星图识别服务，可上传星空图像解算视场指向，用于验证星敏感器算法；源码对应开源项目 astrometry.net。镜像收录自 http://nova.astrometry.net/ ，License 以源仓库 LICENSE 为准 |
| 将项目设为私有 | 不勾选 |
| 该仓库将是一个镜像 | **勾选**（仓库只读，每 8 小时自动与源站同步） |
| 项目类别 | 姿控算法 |
| 项目语言 | 以源仓库为准 |

## 导入后上架专区

1. 人工确认 astrometry.net 源码仓库后再执行导入，导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「姿控算法」→ 保存

## 许可证核查（2026-08-10）
- 结果：非仓库来源（在线服务 http://nova.astrometry.net/ ，按规则不做仓库探测）
- 结论：在线服务本身不适用镜像，专区只收录链接；如需镜像其源码 astrometry.net，须先人工确认官方仓库地址并单独核查许可证后再决定
