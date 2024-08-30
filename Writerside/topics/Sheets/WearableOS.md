<link-summary>可穿戴设备操作系统及评级</link-summary>

# 可穿戴设备操作系统

## 商业操作系统

| 名称(排名不分先后)                                      | 厂商                  | 支持产品                                                                                    | 开放性                               |
|-------------------------------------------------|---------------------|-----------------------------------------------------------------------------------------|-----------------------------------|
| watchOS                                         | Apple Inc.          | Apple Watch全系                                                                           | Lv2.                              |
| [Wear OS by Google](WearOSbyGoogle.md)          | Google LLC          | PixelWatch系列，Galaxy Watch部分型号，<br />小米手表(XMWT01)，TicWatch Pro系列等                        | Lv4.                              |
| Fitbit OS                                       | Fitbit              | Fitbit手表                                                                                | Lv2.                              |
| MIUI For Watch<br />(Wear OS by Google)         | 小米/Xiaomi           | 小米手表(XMWT01)                                                                            | Lv4.                              |
| Magic OS for Watch                              | 荣耀/HONOR            | HONOR Watch 4                                                                           | Lv0.                              |
| TicWearGT OS                                    | 出门问问/Mobovi         | TicWatch GTW                                                                            | Lv0.                              |
| TizenOS                                         | Samsung             | Galaxy Watch部分型号                                                                        | Lv2.                              |
| 湃心OS(PersimWearOS)                              | RT-Thread           | [vivo WATCH 2](vivo-WATCH-2.topic)                                                      | Lv1/Lv0(vivo WATCH2)              |
| [Xiaomi HyperOS](Xiaomi-Hyper-OS.topic)(Vela)   | Xiaomi              | Xiaomi Watch S1 Pro, Xiaomi Watch S3及<br />后续产品                                         | Lv3.                              |
| [HarmonyOS(LiteOS/AOSP)](HarmonyOS_Watch.md)    | HUAWEI              | 华为手表全系，手环7及以后产品                                                                         | Lv3.(LiteOS)<br />Lv4.(With AOSP) |
| OpenHarmony(海思方案)                               | OpenAtom Foundation | 诺希N18, Astrolink S                                                                      | Lv2.                              |
| GarminConnect                                   | 佳明/Garmin           | Garmin手表全系                                                                              | Lv2.(Unstable)                    |
| [ColorOS Watch](ColorOSWatch.md)                | OPPO                | OPPO Watch全系                                                                            | Lv4.                              |
| MIUI Watch(S1 Pro为[Xiaomi Vela](XiaomiVela.md)) | Xiaomi              | 小米手表除XMWT01，Color一代外所有产品                                                                | Lv4.(vela)                        |
| [ZeppOS](ZeppOS.md)                             | 华米/Amazfit          | 详见[ZeppOS文档](https://docs.zepp.com/zh-cn/docs/reference/related-resources/device-list/) | Lv4S.                             |
| AmazfitOS                                       | 华米/Amazfit          | /                                                                                       | Unknown                           |
| BlueOS                                          | vivo                | vivo WATCH 3及后续机型                                                                       | Lv3.                              |
| GS Fit Platform                                 | 光速时代                | /                                                                                       | Lv1.                              |

## 开源操作系统

| 名称(排名不分先后)  | 支持产品                                     | 开放性        |
|-------------|------------------------------------------|------------|
| AsteriodOS  | [支持的产品](https://asteroidos.org/watches/) | Lv4(无应用市场) |
| Wearfit OS  | /                                        | Lv1.       |
| pebble OS   | Pebble系列手表                               | Unknown    |
| InfiniTime  | PineTime智能手表                             | Unknown    |
| WSAP OS     | /                                        | Unknown    |
| OpenHarmony | /                                        | Lv2.       |

## 开放性评级

| 等级    | 描述                                    | 示例                             |
|-------|---------------------------------------|--------------------------------|
| Lv0.  | 应用市场：不支持 第三方应用支持：No(仅预装的应用)           | 小米手环7以前的操作系统 vivo WATCH2上的湃心OS |
| Lv1.  | 应用市场：不支持 第三方应用支持：Yes(可自行安装,但非官方支持¹)   | 小米手环7上的ZeppOS                  |
| Lv2.  | 应用市场：支持 第三方应用支持：Yes(不可自行随意安装)         | GarminConnect，watchOS          |
| Lv2+  | 应用市场：支持 第三方应用支持：Yes(非官方支持且开发难度较大)     | 70mai平台                        |
| Lv3.  | 应用市场：支持 应用支持：Yes(也可自行安装但非官方支持)        | Xiaomi Vela                    |
| Lv4.  | 应用市场：支持 应用支持：Yes(可自行安装)               | HarmonyOS(AOSP)                |
| Lv4S. | 应用市场：支持(应用市场对个人开发者友好) 应用支持：Yes(可自行安装) | ZeppOS, Wear OS by Google      |

Tips:

1. 官方支持的类型:

- 提供开发者模式
- (如果有)应用市场对个人开发者友好
