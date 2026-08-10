# N7 Space 组织调研与社区收录建议

> 调研日期：2026-08-10
> 来源：[https://github.com/n7space](https://github.com/n7space)（GitHub API）
> 用途：为「航天开源社区」专区收录决策提供依据
> 组织属性：外国公司组织（波兰），建议按"社区镜像/收录"处理，不冒充官方入驻

---

## 一、组织概况

**N7 Space sp. z o.o.（N7 Space）** 是波兰一家专注于航天软件与星载计算的公司，成立于 2018 年，官网 [https://n7space.com/](https://n7space.com/) 。

组织在 GitHub 上公开 57 个仓库，覆盖：星载实时操作系统、安全关键软件、ECSS 标准（PUS-C/ASN.1）、CCSDS 协议（CFDP/SpaceWire）、TASTE 工具链、板级支持包（BSP）与开发环境等方向。N7 Space 与欧洲航天局（ESA）、欧空局工具链生态（TASTE）有深度合作，是 TASTE 工具链的重要贡献者之一。

**重点方向与专区分类的对应关系：**

| N7 Space 技术方向 | 对应专区分类 |
| :--- | :--- |
| aerugo（Rust 实时操作系统） | 操作系统 |
| OBCP 星上程序引擎（MicroPython） | 星务处理 |
| PUS-C / ASN.1（ECSS 标准实现） | 数据管理 / 测控通信 |
| CCSDS CFDP / SpaceWire 实现 | 测控通信 |
| TASTE 工具链 / 编译 / 验证工具 | 地面测试 |
| 板级支持包（SAMV71/SAMRH71/LEON3） | 整星设计 / 星务处理 |

---

## 二、组织描述（可直接用于社区"组织/合作方"展示）

> N7 Space 是波兰一家专注航天软件与星载计算的工程公司，成立于 2018 年。公司围绕星载实时操作系统、安全关键软件、ECSS/CCSDS 标准实现与 TASTE 开发工具链开展研发，与欧洲航天局（ESA）保持深度合作。本组织以收录与镜像方式展示 N7 Space 的开源项目，并明确标注原始组织、官方仓库与开源许可证；项目版权与维护权仍归 N7 Space 所有。

---

## 三、可搬运项目清单（有明确开源协议）

> 判定标准：仓库带有明确的 SPDX 开源许可证；NOASSERTION/无 LICENSE 的不建议直接搬运代码，仅可作链接收录。

### A 类：推荐搬运（有明确协议 + 与专区定位契合 + 知名度较高）

| 仓库 | 协议 | 语言 | 一句话描述 | 建议分类 |
| :--- | :--- | :--- | :--- | :--- |
| `aerugo` | Apache-2.0 | Rust | 面向安全关键应用、用 Rust 编写的实时操作系统（RTOS） | 操作系统 |
| `n7s-obcp` | MIT | C | 基于 MicroPython 的 OBCP 星上程序执行引擎（ESA 合同资助） | 星务处理 |
| `taste-obcp` | MIT | C | TASTE 的 OBCP 组件（MicroPython 嵌入移植） | 星务处理 |
| `asn1-pusc-lib` | GPL-3.0 | C | 使用 ACN 编码实现 PUS-C ECSS 标准的 ASN.1 库 | 数据管理 |
| `taste-canopen` | Apache-2.0 | C | TASTE 的 CANopen 组件 | 测控通信 |
| `TASTE-Dev-Env` | LGPL-2.1 | Dockerfile | TASTE 开发环境（Docker） | 地面测试 |
| `TASTE-SAMV71-Demo` | GPL-3.0 | QMake | SAMV71 TASTE 运行时与驱动使用演示 | 地面测试 |
| `Capella-TASTE-Plugin` | EPL-1.0 | Java | Capella 模型导出到 TASTE 的插件 | 地面测试 |
| `asn1scc.Fuzzer` | GPL-3.0 | C++ | 基于 ASN.1/ACN 模型的测试用例生成与畸形数据模拟工具 | 地面测试 |
| `asn1scc.IDE` | GPL-3.0 | C++ | asn1scc 的 Qt Creator 插件（嵌入式 ASN.1/ACN 编译器 IDE） | 地面测试 |
| `Leon3-BSP` | GPL-2.0 | C | LEON3 处理器板级支持包 | 整星设计 |
| `TASTE-LEON3-Drivers` | GPL-2.0 | C | TASTE LEON3 驱动 | 整星设计 |
| `Remote-Target-Runner` | GPL-2.0 | Python | 远程目标运行工具 | 地面测试 |
| `TASTE-Runtime-Tests` | GPL-2.0 | C | TASTE 运行时测试 | 地面测试 |

### B 类：可搬运但优先级较低（有协议，但多为工具链配套/重复度高）

| 仓库 | 协议 | 语言 | 说明 | 建议分类 |
| :--- | :--- | :--- | :--- | :--- |
| `FreeRTOS-Kernel` | MIT | C | FreeRTOS 官方内核的镜像 fork，建议收录原始仓库而非此 fork | 操作系统 |
| `cmake-tools` | MIT | CMake | CMake 工具 | 地面测试 |
| `xmldiff` | MIT | Python | XML 差异对比库（通用工具，与航天相关性低） | 地面测试 |
| `rtems-atsamv-dev-env` | MIT | Dockerfile | RTEMS 开发环境（SAMV71Q21） | 地面测试 |
| `adac-hybrid-arm` | GPL-3.0 | Ada | Ada 交叉编译包装 | 地面测试 |
| `MSP430-Emulator` | GPL-3.0 | C | TI MSP430 软件仿真模型 | 地面测试 |
| `sdl2promela` | GPL-3.0 | C | SDL 到 Promela 转换 | 地面测试 |
| `sis` | GPL-3.0 | C | 工具链组件 | 地面测试 |
| `AURORA-Reference-Component-Set` | GPL-3.0 | C | AURORA 参考组件集 | 星务处理 |
| `AURORA-Validation` | GPL-3.0 | C | AURORA 验证组件 | 地面测试 |

### C 类：不建议搬运代码（协议不明确 NOASSERTION / 无 LICENSE），仅作链接收录

- `asn1scc`（F#，ASN.1 编译器，**NOASSERTION**，需确认实际授权条款后再考虑）
- `n7s-cfdp`（C，CCSDS CFDP 实现，**NOASSERTION**）
- `n7s-spw`（C，SpaceWire 实现，**NOASSERTION**）
- `n7s-LibmCS`（C，**NOASSERTION**）
- `DataModellingTools`（Python，ESA TASTE 工具链 fork，**NOASSERTION**）
- `Spin`（Promela，模型检测工具，**NOASSERTION**）
- `arm-bsp`（C，SAMV71/SAMRH71 BSP，**NOASSERTION**）
- `TASTE-Linux-Runtime`、`TASTE-Linux-Drivers`、`TASTE-SAMV71-Runtime`、`TASTE-SAMV71-Drivers`、`TASTE-LEON3-Runtime`、`taste-memory-access` 等（无 LICENSE 或 NOASSERTION）
- `linux`（Linux 内核镜像，不建议镜像整库）

---

## 四、收录建议总结

1. **优先搬运 A 类**，尤其是 `aerugo`（Apache-2.0，Rust RTOS，与"操作系统"分类高度契合）和 `n7s-obcp`（MIT，星上程序引擎）。
2. 搬运时勾选"镜像"，保留原始组织、官方仓库链接、许可证与版权声明，并在简介中注明"社区镜像（N7 Space）"。
3. **GPL 系（GPL-2.0/GPL-3.0/LGPL）项目**：可镜像展示，但镜像本身也受 GPL 传染约束——镜像仓库应保持同一许可证，不混入其他许可代码；如后续有分发/修改需求需按 GPL 履行义务。
4. **NOASSERTION/无 LICENSE 项目**：只做"链接收录"（在项目卡片放原始链接），不复制代码，避免版权风险。
5. N7 Space 为国外组织，暂不建议推进"官方入驻"，按社区镜像策略处理即可。
6. `FreeRTOS-Kernel`、`linux` 等属于上游官方仓库的镜像，建议收录上游原始仓库（FreeRTOS/FreeRTOS、torvalds/linux），不要收录此 fork，避免重复与维护混乱。

---

## 五、待确认事项

- [ ] 确认 `asn1scc`、`n7s-cfdp` 等 NOASSERTION 仓库是否在仓库内 README/LICENSING 中另行声明了授权（GitHub API 的 license 字段为空不代表无授权，需人工查看仓库根目录）
- [ ] `aerugo` 项目当前维护状态与 star 数（如作为重点收录，建议补记社区关注度数据）
- [ ] 如需与 N7 Space 建立合作，可经其官网 n7space.com 联系
