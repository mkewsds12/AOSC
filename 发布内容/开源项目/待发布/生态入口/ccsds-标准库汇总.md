# CCSDS 标准库汇总

> 板块：项目管理 / 生态入口
> 来源：https://github.com/topics/ccsds
> 状态：待发布（收录线索，不建镜像组织）
> ⚠️ 非 git 仓库地址，不能直接镜像导入

## 项目简介

本条目是 GitHub 的 CCSDS topic 入口页，聚合了社区各类 CCSDS 标准开源实现，是跟踪 CCSDS 生态的索引线索。不能整体镜像导入，建议从下方重点仓库中挑选逐个镜像收录，或仅作为生态导航在专区内容中引用。

## 可参考的重点仓库（仓库名以实际为准，导入前需人工确认）

| 仓库 | 说明 | 语言 |
|------|------|------|
| https://github.com/us-irs/CCSDSPy | CCSDS 包解析 | Python |
| https://github.com/dariol83/ccsds | Java CCSDS/SLE 框架 | Java |
| https://github.com/us-irs/spacepackets-rs / space_packet_parser | 空间包解析 | Rust/Python |
| https://github.com/dariol83/ccsds（sle-provider） | SLE 服务提供端 | Java |
| ccsds-ndm | 轨道数据消息 NDM | 以源仓库为准 |
| puslib | ECSS PUS 服务实现 | 以源仓库为准 |
| ccsds-spacepacket | 空间包 Rust 实现 | Rust |

## GitLink 导入填写指南

该来源为 topic 入口页，无法整体镜像。处理方式二选一：

1. **保留线索**：本文件仅作为收录线索存档，不执行导入
2. **逐个导入**：从上表挑选重点仓库（如 CCSDSPy、ccsds-spacepacket），各自按标准镜像流程创建独立项目，表单参照本目录其他项目模板，项目类别选「测控通信」，语言按各仓库实际填写

## 导入后上架专区

1. 导入完成后核对 README / LICENSE 是否同步正常
2. 专区管理后台 → 项目管理 → 项目列表 → 添加项目 → 搜索本项目 → 分类选「测控通信」→ 保存

## 许可证核查（2026-08-10）
- 结果：非仓库来源（来源为 GitHub topic 汇总页 https://github.com/topics/ccsds，非单一 git 仓库）
- 结论：无需镜像，保持链接收录即可；表中列出的各具体仓库如需单独镜像，须逐一按其仓库 LICENSE 核查
