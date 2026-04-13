# RuyiSDK 👋

## Introduction

RuyiSDK is a product plan for an all-in-one RISC-V integrated development environment. Starting from 2023, it plans to provide RISC-V developers with a complete, full-stack, and fully-functional development environment within three years, including a full suite of tools from compilation, debugging to simulation, and plans to support the mainstream RISC-V development boards on the market.

RuyiSDK mainly includes a component manager (also known as a package manager), a graphical integrated development environment (IDE), and a developer community.

At present, the component manager has integrated common software such as compilation toolchains, debugging tools, and simulator software, and has a supporting management tool ruyi, which can provide developers with a variety of common functions such as package information query, installation, and uninstallation. RISC-V developers can already quickly build a RISC-V development environment through the command line tool ruyi.

Furthermore, RuyiSDK also provides a wizard-style system installation tool, which currently supports more than 20 common RISC-V development boards and provides a one-stop image installation service for them.

The RuyiSDK graphical integrated development environment is still in the planning stage.

## Access and Download

Learn about RuyiSDK starting from the [RuyiSDK official website](https://ruyisdk.org/)!

If you want to install the compilation toolchain, debugging tools, simulators, and other software that support RISC-V, you can start with [downloading](https://ruyisdk.org/download/) and using ruyi.

If you want to install an image for your RISC-V development board, you can use the `ruyi device provision` command to view the RISC-V development boards and the currently available different operating systems for them. This program will guide you through the device selection, system image selection, and installation.

If your device is not in the supported list, you can submit your feedback in [ruyisdk.cn](https://ruyisdk.cn/) or [Discussions](https://github.com/ruyisdk/ruyisdk/discussions).

If you want to learn more about the adaptation of RISC-V operating systems to RISC-V development boards, you can check the [Operating System Support Matrix](https://github.com/ruyisdk/support-matrix/).

## Updates

Starting from January 2024, the RuyiSDK project adopts a rapid iteration management method, releasing a version approximately every two weeks (postponed during statutory holidays).

Currently, the package manager can obtain the latest version and version change information through [ruyi release](https://github.com/ruyisdk/ruyi/releases).

More content can be found in the [RuyiSDK BiWeekly Report](https://github.com/ruyisdk/wechat-articles).

## Usage

The ruyi tool currently supports x86_64, aarch64, and riscv64 architectures, and supports various Linux distributions such as [openRuyi](https://github.com/openRuyi-Project/openRuyi), Debian ([RevyOS](https://github.com/revyos)), Ubuntu, openEuler, Fedora, ArchLinux, Gentoo, and openKylin, it has good architecture compatibility and platform compatibility, please install and use with confidence.

More ruyi usage [documentation](https://ruyisdk.org/en/docs/Package-Manager/).

## Contact

Friends interested in RuyiSDK can follow and join us through the following channels:

- Follow the WeChat public account: RUYISDK
- Send an email to [contact@ruyisdk.cn](mailto:contact@ruyisdk.cn)

## Related Projects

* [RuyiAI](https://github.com/RuyiAI-Stack) AI System Software Stack for RISC-V Architecture.
* [openRuyi](https://github.com/openRuyi-Project) An open, rolling Linux distribution project for RISC-V.
* [RVCK](https://github.com/RVCK-Project/rvck) RISC-V Common Kernel Project.
