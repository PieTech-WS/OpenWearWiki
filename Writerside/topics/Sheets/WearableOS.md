# 可穿戴设备操作系统

| 名称(排名不分先后)                                               | 厂商         | 支持产品                                                                                    | 开放性                                           |
|----------------------------------------------------------|------------|-----------------------------------------------------------------------------------------|-----------------------------------------------|
| watchOS                                                  | Apple Inc. | Apple Watch全系                                                                           | Lv2.                                          |
| Wear OS<br />by Google                                   | Google LLC | PixelWatch系列，Galaxy Watch部分型号，<br />小米手表(XMWT01)，TicWatch Pro系列等                        | Lv4.                                          |
| MIUI For Watch<br />(Wear OS by Google)                  | Xiaomi     | 小米手表(XMWT01)                                                                            | Lv4.                                          |
| TizenOS                                                  | Samsung    | Galaxy Watch部分型号                                                                        | Unknown                                       |
| 湃心OS(PersimWearOS)                                       | RT-Thread  | vivo WATCH 2                                                                            | Lv1/Lv0(vivo WATCH2)                          |
| [Xiaomi Vela(NuttX)](XiaomiVela.md)                      | Xiaomi     | Xiaomi Watch S1 Pro，小米手环8 Pro                                                           | Lv4.                                          |
| Xiaomi HyperOS                                           | Xiaomi     | Xiaomi Watch S3                                                                         | Lv4.                                          |
| [HarmonyOS(LiteOS/OpenHarmony/AOSP)](HarmonyOS_Watch.md) | HUAWEI     | 华为手表全系，手环7及以后产品                                                                         | Lv2.(LiteOS/OpenHarmony)<br />Lv4.(With AOSP) |
| GarminConnect                                            | 佳明/Garmin  | Garmin手表全系                                                                              | Lv2.(Unstable)                                |
| ColorOS Watch                                            | OPPO       | OPPO Watch全系                                                                            | Lv4.                                          |
| MIUI Watch(S1 Pro为Xiaomi Vela)                           | Xiaomi     | 小米手表除XMWT01，Color一代外所有产品                                                                | Lv4.(vela)                                    |
| ZeppOS                                                   | 华米/Amazfit | 详见[ZeppOS文档](https://docs.zepp.com/zh-cn/docs/reference/related-resources/device-list/) | Lv4S.                                         |
| AmazfitOS                                                | 华米/Amazfit | /                                                                                       | Unknown                                       |

## 开放性评级

| 等级  | 描述                                                                    | 示例                                               |
| ----- | ----------------------------------------------------------------------- | -------------------------------------------------- |
| Lv0.  | 应用市场：不支持<br />应用支持：仅预装的应用                            | 小米手环7以前的操作系统<br />vivo WATCH2上的湃心OS |
| Lv1.  | 应用市场：不支持<br />应用支持：Yes(可自行安装,但非官方支持¹)          | 小米手环7上的ZeppOS                                |
| Lv2.  | 应用市场：支持<br />应用支持：Yes(不可自行随意安装)                     | GarminConnect，watchOS                             |
| Lv3.  | 应用市场：支持<br />应用支持：Yes(也可自行安装但非官方支持)             | Xiaomi Vela                                        |
| Lv4.  | 应用市场：支持<br />应用支持：Yes(可自行安装)                           | HarmonyOS(AOSP)                                    |
| Lv4S. | 应用市场：支持(应用市场对个人开发者友好)<br />应用支持：Yes(可自行安装) | ZeppOS, Wear OS by Google                          |

Tips:

1. 官方支持的类型:
 - 提供开发者模式
 - (如果有)应用市场对个人开发者友好