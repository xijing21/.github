# RuyiSDK

## 介绍

RuyiSDK 是一个一体化RISC-V集成开发环境的产品计划。从 2023 年开始筹备，计划用三年时间为 RISC-V 开发者提供一个完整的、全家桶式的全功能开发环境，包含从编译、调试到仿真的全套工具,并计划支持市面上主流的 RISC-V 开发板。

RuyiSDK 主要包含了一个组件管理器（也称为包管理器）、一个图形化的集成开发环境（IDE）、一个开发者交流社区。

目前，组件管理器已经集成了编译工具链、调试工具、模拟器软件等常用软件，并拥有了配套管理工具 ruyi ，能为开发者提供诸如软件包信息查询、安装、卸载等多种常用功能。RISC-V 开发者已经能够通过命令行工具 ruyi 快速搭建 RISC-V 开发环境。

此外，RuyiSDK 还提供了一个向导式的系统安装工具，目前已经支持了20余款常见RISC-V开发板，为它们提供一站式镜像安装服务。

RuyiSDK 图形化集成开发环境还在筹备中。

## 访问与下载

了解 RuyiSDK 从 [RuyiSDK官网](https://ruyisdk.org/) 开始！

如果您想要安装支持 RISC-V 的编译工具链、调试工具、模拟器等软件，可从[下载](https://ruyisdk.org/download/) 安装和使用 ruyi 开始。

如果您想要为您的 RISC-V 开发板安装镜像，可以通过 `ruyi device provision` 查看RISC-V开发板及其目前所有可用的不同操作系统，该程序将引导您完成设备选择、系统镜像选择和安装。如果您的设备不在支持列表中，可以将需求在 [RuyiSDK 技术论坛](https://ruyisdk.cn/) 或 [Discussions](https://github.com/ruyisdk/ruyisdk/discussions) 中进行反馈。

如果您想要更广泛的了解RISC-V操作系统对RISC-V开发板适配简况，可以通过 [操作系统支持矩阵](https://github.com/ruyisdk/support-matrix/)了解。

## 更新

自2024年1月开始，RuyiSDK 项目采用快速迭代的管理方式，大约每两周发布一个版本（法定节假日顺延）。

当前，包管理器可通过 [ruyi release](https://github.com/ruyisdk/ruyi/releases) 。

更多内容可关注 [RuyiSDK双周进展汇报](https://github.com/ruyisdk/wechat-articles) 。

## 使用

ruyi 工具目前支持 x86_64、aarch64、riscv64 三种架构，支持 [openRuyi](https://github.com/openRuyi-Project/openRuyi), Debian ([RevyOS](https://github.com/revyos))、Ubuntu、openEuler、Fedora 、ArchLinux 、Gentoo、openKylin 等多种Linux发行版，具有良好的架构兼容性和平台兼容性，请放心地安装使用。

更多 ruyi [使用文档](https://ruyisdk.org/docs/Package-Manager/)。

## 联系

对 RuyiSDK 感兴趣的朋友可以通过以下方式关注和加入我们：

- 关注微信公众号：RUYISDK
- 发送邮件至 [contact@ruyisdk.cn](mailto:contact@ruyisdk.cn)

## 相关项目

* [RuyiAI](https://github.com/RuyiAI-Stack) RISC-V 架构的 AI 系统软件栈。
* [openRuyi](https://github.com/openRuyi-Project) 面向 RISC-V 的开源滚动发行版。
* [RVCK](https://github.com/RVCK-Project/rvck) RISC-V 内核同源项目。
