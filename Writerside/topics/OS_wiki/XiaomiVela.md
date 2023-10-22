# Xiaomi Vela

> Xiaomi Vela是小米基于开源实时操作系统NuttX打造的物联网嵌入式软件平台，Vela在各种物联网硬件平台上提供统一的软件服务，支持丰富的组件和易用的框架，打通碎片化的物联网应用场景。——Xiaomi Vela 官方网站¹

> 本文仅介绍其在可穿戴设备上的情况与应用

Xiaomi Vela是小米公司开发的可用于可穿戴设备的操作系统，基于NuttX。适用于基于蓝牙SoC的可穿戴设备平台。

## 概览

| 项目     | 信息                                                                                             |
| -------- | ------------------------------------------------------------------------------------------------ |
| 名称     | Xiaomi Vela(在手表上，常使用MIUI Watch名称，<br />但使用MIUI Watch的手表不一定是搭载Xiaomi Vela) |
| 开发者   | 小米公司                                                                                         |
| 底层     | NuttX                                                                                            |
| 应用支持 | 是(Vela快应用)                                                                                   |
| 适用于   | 可穿戴设备(基于蓝牙SoC,轻智能手表/手环)                                                          |
| 开放性² | Lv2.                                                                                             |

## 支持的设备列表

| 设备名称           | 型号    |
| ------------------ | ------- |
| Xiaomi Watch S1Pro | M2134W1 |
| 小米手环8 Pro      | M2303B1 |

## 应用支持

Xiaomi Vela提供了一套完整的快应用开发、运行支持，名为Xiaomi Vela快应用。其支持使用HTML+CSS+JavaScript进行开发构建应用以运行在可穿戴设备上，为可穿戴设备提供功能上的扩展。拥有基于Visual Studio Code的IDE和基于QEMU的模拟器，可在Ubuntu 20.04操作系统上运行。同时支持将原有基于70mai平台的手表应用轻松转移到Vela快应用，减少重新开发的成本。

开发文档：[概述 · Xiaomi Vela 快应用开发文档](https://iot.mi.com/vela/quickapp/zh/content/intro.html "点击访问")

## Wiki Note

版本 1.0-2023/8/18

### 更新日志

- 1.0 初始版本发布。2023/8/18

### 贡献者

[yizigezi](mailto://yizigezi@outlook.com "发送邮件")
