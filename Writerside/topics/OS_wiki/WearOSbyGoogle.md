# Wear OS by Google(Android Wear)

**[贡献者](wearosbygoogle_authors.md)**

Wear OS by Google(曾用名Android Wear)是由Google LLC开发的智能可穿戴设备操作系统，基于Android。

## 概览

| 项目                   | 信息                                                     |
|----------------------| -------------------------------------------------------- |
| 名称                   | Wear OS by Google(Android Wear)                          |
| 开发者                  | Google LLC                                               |
| 底层                   | Android                                                  |
| 当前最新版本               | Wear OS 4(Android 13)                                    |
| 应用支持                 | 是(Wear OS应用，部分Android应用)                         |
| 适用于                  | 全智能手表(一般为SAMSUNG Exynos或高通骁龙Wear/W系列平台) |
| [开放性](WearableOS.md) | Lv4S.                                                    |

## 发展

- 2014年03月19日，Google发布Android Wear.
- 2018年3月16日，Google宣布其于2014 年推出智能手表操作系统 Android Wear 将正式更名为 Wear OS。
- 2021 年**Google I/O** 大会上，Google宣布了**Wear OS 3.0**。
- 5 月 13 日消息，在 I / O 2023 开发者大会上，谷歌宣布了 Wear OS 4 系统，将于今年晚些时候推出，并承诺提供更好用的手表应用程序套件、改进电池管理和更好可访问性以及改进后的 TTS (IT之家注：text-to-speech，文字转语音) 输入。谷歌尚未宣布 Wear OS 4 正式版的具体发布时间，预计三星 Galaxy Watch 6 系列手表和谷歌 Pixel watch 2 等将率先搭载 Wear OS 4。

## 支持的设备列表

暂时列不出来喵(这个是一个大坑)

## 应用支持

Wear OS by Google的应用支持有些复杂。

安卓应用大多可以在Wear OS上使用，但是Wear OS不支持有一部分的安卓特性，例如WebView。你为其他Android手表系统甚至是手机系统开发的应用(如ColorOS)，大概率可以在Wear OS上使用。但是如果应用是根据Google的Wear OS应用开发指南开发的，那么大概率无法在其他Android手表上使用，因为Wear OS有Android不支持的API。

## 用户体验

### 界面

Wear OS通常有以下界面(以小米手表，Wear OS 2.27为例):

- 表盘
- 控制中心(从表盘上划)
- 消息中心(从表盘下划)
- 负一屏(从表盘右划)
- 卡片(从表盘左划)
- 应用列表(点按右上旋钮/按钮)
- 电源菜单(长按右下按钮)
- 快捷操作(点按右下按钮)

**注意:Wear OS在之前的界面体验趋于统一，但是现在部分厂商自定义了很多操作逻辑和界面风格，例如三星的One UI Watch。**

在之前，小米曾做过类似的行为，在系统应用内使用自己的界面风格，但是由于之前Google的限制，反而使得界面体验割裂。

### 功能

- 均内置Google Play服务，在国外体验不错(国内版本为半残废)
- 专为智能手表设计
- 支持开发者模式，支持通过蓝牙、WiFi和USB等方式进行调试
- 独立使用能力强

### 槽点

- 需要同时连接Wear OS by Google应用和厂商的应用
- 国内版开启Google Play需要换版本
- 更新不积极
- 一些操作逻辑令人头疼
- 更换手机需要将手表恢复出厂设置(在Wear OS 4已优化)
- 国内厂商使用容易寄。如果厂商使用Google的OTA服务器(例如小米)，那么更新服务就可能已经寄了，因为Google的服务器被监管了。当然厂商也可以使用自己的服务器。¹

## 注释

1.小米为何没有切换为自己的服务器, 请看[设备Wiki中小米手表](XiaomiWatch.md)的情报站一节。
