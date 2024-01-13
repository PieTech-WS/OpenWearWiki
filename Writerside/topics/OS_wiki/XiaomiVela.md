# Xiaomi Vela

> Xiaomi Vela是小米基于开源实时操作系统NuttX打造的物联网嵌入式软件平台，Vela在各种物联网硬件平台上提供统一的软件服务，支持丰富的组件和易用的框架，打通碎片化的物联网应用场景。——Xiaomi
> Vela 官方网站¹

> 欲了解更多关于其在可穿戴设备上的应用, 请移步[Xiaomi HyperOS](Xiaomi-Hyper-OS.topic)

Xiaomi Vela是小米公司开发的可用于可穿戴设备的操作系统，基于NuttX。适用于基于蓝牙SoC的可穿戴设备平台。

## 概览

| 项目   | 信息                                                                                 |
|------|------------------------------------------------------------------------------------|
| 名称   | Xiaomi Vela(在手表上，常使用MIUI Watch或Xiaomi HyperOS名称，但使用MIUI Watch的手表不一定是搭载Xiaomi Vela) |
| 开发者  | 小米公司                                                                               |
| 底层   | NuttX                                                                              |
| 应用支持 | 是(Vela快应用)                                                                         |
| 适用于  | 可穿戴设备(基于蓝牙SoC,轻智能手表/手环)                                                            |
| 开放性² | Lv2.                                                                               |
| 开源协议 | Apache License 2.0                                                                 |


Xiaomi Vela本身是一个基于NuttX的RTOS.

NuttX是由Gregory Nutt最初开发并开源在GitHub上的一个开源RTOS, 兼容POSIX标准(这是小米选择这款系统作为底层的原因).之后在小米的推动下,
NuttX被捐献给了Apache基金会并以Apache License 2.0开源.

Xiaomi Vela一开始只是用于小米的物联网设备, 例如FIVE智能刀筷杀菌架, 小米小爱音箱Play增强版, 依靠Vela IoT模组运行.然后在Xiaomi手表S1 Pro上, 小米首次将Xiaomi Vela
用于了可穿戴设备.随后使用Vela的是小米手环8 Pro, Watch S3和Redmi Watch 4.所有搭载Vela的设备均支持Vela快应用.关于Vela快应用, 详见[HyperOS应用支持](Xiaomi-Hyper-OS.topic#third-party-app-support)
随着Xiaomi HyperOS的发布, 小米的可穿戴设备可能会长期使用Xiaomi Vela.这不失为是Vela快应用生态发展的一支强心剂.

## WikiNotes {collapsible="true" default-state="expanded"}
版本1.0-2023/8/18
### 贡献者 {collapsible="true" default-state="collapsed" id="authors"}
[yizigezi](mailto://yizigezi@outlook.com "发送邮件")
### 更新日志 {collapsible="true" default-state="collapsed" id="versionLogs"}
- 1.0 初始版本发布。2023/8/18


