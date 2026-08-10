# n7space 项目导入清单（GitLink 表单字段整理）

> 整理日期：2026-08-10
> 适用：GitLink 特色专区「航天开源社区」→ 导入项目
> 说明：拥有者请按实际账号/组织填写（如导入到自己的组织）；以下按 GitLink 导入表单字段逐项整理
> 镜像建议：全部勾选"该仓库将是一个镜像"（只读 + 每 8 小时自动同步）

---

## A 类：重点导入（14 个，协议明确 + 与专区定位契合）

### 1. aerugo

- 导入仓库URL：`https://github.com/n7space/aerugo.git`
- 拥有者：你的组织 / 项目名称：`aerugo`
- 项目标识：`aerugo`
- 项目简介：N7 Space 用 Rust 编写的实时操作系统（RTOS），面向安全关键应用，为星载软件提供内存安全、强实时与高可靠的基础软件底座。
- 项目类别：操作系统
- 项目语言：Rust
- 协议：Apache-2.0

### 2. n7s-obcp

- 导入仓库URL：`https://github.com/n7space/n7s-obcp.git`
- 拥有者：你的组织 / 项目名称：`n7s-obcp`
- 项目标识：`n7s-obcp`
- 项目简介：基于 MicroPython 的 OBCP 星上程序执行引擎，由 ESA 合同资助开发，支持星上程序按需加载与执行。
- 项目类别：星务处理
- 项目语言：C
- 协议：MIT

### 3. taste-obcp

- 导入仓库URL：`https://github.com/n7space/taste-obcp.git`
- 拥有者：你的组织 / 项目名称：`taste-obcp`
- 项目标识：`taste-obcp`
- 项目简介：TASTE 工具链的 OBCP 组件，基于 MicroPython 嵌入移植，提供星上程序执行能力。
- 项目类别：星务处理
- 项目语言：C
- 协议：MIT

### 4. asn1-pusc-lib

- 导入仓库URL：`https://github.com/n7space/asn1-pusc-lib.git`
- 拥有者：你的组织 / 项目名称：`asn1-pusc-lib`
- 项目标识：`asn1-pusc-lib`
- 项目简介：使用 ACN 编码实现的 PUS-C（ECSS 标准）ASN.1 库，支撑卫星遥测遥控数据模型与协议开发。
- 项目类别：数据管理
- 项目语言：C
- 协议：GPL-3.0

### 5. taste-canopen

- 导入仓库URL：`https://github.com/n7space/taste-canopen.git`
- 拥有者：你的组织 / 项目名称：`taste-canopen`
- 项目标识：`taste-canopen`
- 项目简介：TASTE 工具链的 CANopen 通信组件，用于星载/嵌入式设备现场总线通信。
- 项目类别：测控通信
- 项目语言：C
- 协议：Apache-2.0

### 6. TASTE-Dev-Env

- 导入仓库URL：`https://github.com/n7space/TASTE-Dev-Env.git`
- 拥有者：你的组织 / 项目名称：`TASTE-Dev-Env`
- 项目标识：`taste-dev-env`
- 项目简介：TASTE 开发环境（Docker 镜像），一键搭建欧空局 TASTE 建模-开发-验证工具链。
- 项目类别：地面测试
- 项目语言：Dockerfile
- 协议：LGPL-2.1

### 7. TASTE-SAMV71-Demo

- 导入仓库URL：`https://github.com/n7space/TASTE-SAMV71-Demo.git`
- 拥有者：你的组织 / 项目名称：`TASTE-SAMV71-Demo`
- 项目标识：`taste-samv71-demo`
- 项目简介：SAMV71 平台 TASTE 运行时与驱动的使用演示工程，展示 TASTE 在星载/嵌入式平台上的落地流程。
- 项目类别：地面测试
- 项目语言：QMake
- 协议：GPL-3.0

### 8. Capella-TASTE-Plugin

- 导入仓库URL：`https://github.com/n7space/Capella-TASTE-Plugin.git`
- 拥有者：你的组织 / 项目名称：`Capella-TASTE-Plugin`
- 项目标识：`capella-taste-plugin`
- 项目简介：Capella 建模工具导出到 TASTE 的插件，打通 MBSE 建模到星载软件工程化的链路。
- 项目类别：地面测试
- 项目语言：Java
- 协议：EPL-1.0

### 9. asn1scc.Fuzzer

- 导入仓库URL：`https://github.com/n7space/asn1scc.Fuzzer.git`
- 拥有者：你的组织 / 项目名称：`asn1scc.Fuzzer`
- 项目标识：`asn1scc-fuzzer`
- 项目简介：基于 ASN.1/ACN 模型的测试用例生成与畸形数据模拟工具，用于协议与通信软件健壮性测试。
- 项目类别：地面测试
- 项目语言：C++
- 协议：GPL-3.0

### 10. asn1scc.IDE

- 导入仓库URL：`https://github.com/n7space/asn1scc.IDE.git`
- 拥有者：你的组织 / 项目名称：`asn1scc.IDE`
- 项目标识：`asn1scc-ide`
- 项目简介：asn1scc（嵌入式 ASN.1/ACN 编译器）的 Qt Creator 插件，提供图形化建模与代码生成 IDE 支持。
- 项目类别：地面测试
- 项目语言：C++
- 协议：GPL-3.0

### 11. Leon3-BSP

- 导入仓库URL：`https://github.com/n7space/Leon3-BSP.git`
- 拥有者：你的组织 / 项目名称：`Leon3-BSP`
- 项目标识：`leon3-bsp`
- 项目简介：LEON3 航天处理器的板级支持包（BSP），为星载计算机软件提供底层硬件抽象。
- 项目类别：整星设计
- 项目语言：C
- 协议：GPL-2.0

### 12. TASTE-LEON3-Drivers

- 导入仓库URL：`https://github.com/n7space/TASTE-LEON3-Drivers.git`
- 拥有者：你的组织 / 项目名称：`TASTE-LEON3-Drivers`
- 项目标识：`taste-leon3-drivers`
- 项目简介：TASTE 工具链针对 LEON3 平台的驱动集合，支撑航天级处理器外设访问。
- 项目类别：整星设计
- 项目语言：C
- 协议：GPL-2.0

### 13. Remote-Target-Runner

- 导入仓库URL：`https://github.com/n7space/Remote-Target-Runner.git`
- 拥有者：你的组织 / 项目名称：`Remote-Target-Runner`
- 项目标识：`remote-target-runner`
- 项目简介：远程目标运行工具，支持对远端星载/嵌入式目标板的程序下发与执行控制。
- 项目类别：地面测试
- 项目语言：Python
- 协议：GPL-2.0

### 14. TASTE-Runtime-Tests

- 导入仓库URL：`https://github.com/n7space/TASTE-Runtime-Tests.git`
- 拥有者：你的组织 / 项目名称：`TASTE-Runtime-Tests`
- 项目标识：`taste-runtime-tests`
- 项目简介：TASTE 运行时测试套件，覆盖星载运行时各组件的功能与集成验证。
- 项目类别：地面测试
- 项目语言：C
- 协议：GPL-2.0

---

## B 类：可选导入（有协议，优先级较低）

| 仓库 | URL | 类别 | 语言 | 协议 |
| :--- | :--- | :--- | :--- | :--- |
| FreeRTOS-Kernel | <https://github.com/n7space/FreeRTOS-Kernel.git> | 操作系统 | C | MIT |
| rtems-atsamv-dev-env | <https://github.com/n7space/rtems-atsamv-dev-env.git> | 地面测试 | Dockerfile | MIT |
| xmldiff | <https://github.com/n7space/xmldiff.git> | 地面测试 | Python | MIT |
| cmake-tools | <https://github.com/n7space/cmake-tools.git> | 地面测试 | CMake | MIT |
| MSP430-Emulator | <https://github.com/n7space/MSP430-Emulator.git> | 地面测试 | C | GPL-3.0 |
| sdl2promela | <https://github.com/n7space/sdl2promela.git> | 地面测试 | C | GPL-3.0 |
| sis | <https://github.com/n7space/sis.git> | 地面测试 | C | GPL-3.0 |
| AURORA-Reference-Component-Set | <https://github.com/n7space/AURORA-Reference-Component-Set.git> | 星务处理 | C | GPL-3.0 |
| AURORA-Validation | <https://github.com/n7space/AURORA-Validation.git> | 地面测试 | C | GPL-3.0 |
| adac-hybrid-arm | <https://github.com/n7space/adac-hybrid-arm.git> | 地面测试 | Ada | GPL-3.0 |

> B 类简介可直接复用 A 类同风格一句话（如 FreeRTOS-Kernel：FreeRTOS 内核源码镜像，建议优先收录上游官方仓库）。

---

## C 类：不建议导入代码（NOASSERTION / 无 LICENSE），仅链接收录

- `asn1scc`、`n7s-cfdp`、`n7s-spw`、`n7s-LibmCS`、`DataModellingTools`、`Spin`、`arm-bsp`、`linux` 及多个 TASTE 运行时/驱动（无 LICENSE 或 NOASSERTION）

---

## 填写提示

1. **拥有者**：选你自己的组织/账号（镜像挂到自己名下，但简介中注明原始组织 n7space）。
2. **项目标识**：用英文关键字（如上表），是项目 URL 标识部分，创建后不可随意改。
3. **项目简介**：≤200 字，建议"是什么 + 干什么 + 技术栈"，可在末尾追加"（社区镜像，原始组织：N7 Space，<https://github.com/n7space>）"。
4. **镜像**：全部勾选"该仓库将是一个镜像"，保持只读、每 8 小时自动同步。
5. **GPL 系项目**：镜像仓库保持同一许可证，不混入其他许可代码。
