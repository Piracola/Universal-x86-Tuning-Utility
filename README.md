# Universal x86 Tuning Utility

[![Download Latest](https://img.shields.io/github/downloads/JamesCJ60/Universal-x86-Tuning-Utility/latest/total?style=flat-square&color=orange&label=Download%20Latest)](https://github.com/JamesCJ60/Universal-x86-Tuning-Utility/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/JamesCJ60/Universal-x86-Tuning-Utility/total?style=flat-square&color=orange&label=Download%20Total)](https://github.com/JamesCJ60/Universal-x86-Tuning-Utility/releases/latest)
[![discord](https://img.shields.io/discord/772105072720871435?color=orange&label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/9FeYVcbbUQ)
[![Donations](https://img.shields.io/badge/PayPal-00457C?style=flat-square&color=orange&label=Donations&logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/JamesCJ60)
[![Support us on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Duxtusoftware%26type%3Dpatrons&style=flat-square&color=orange&label=Patreon&logoColor=white)](https://patreon.com/uxtusoftware)

![Github banner #2](https://github.com/JamesCJ60/Universal-x86-Tuning-Utility/assets/20888782/2b3256b6-814e-47ca-bfa8-ff07636d63de)

本项目仍在开发中！

请注意：本软件按"原样"提供，不提供任何明示或暗示的保证，包括但不限于适销性、特定用途适用性和非侵权性的保证。滥用本软件可能导致系统不稳定或故障。

如果您在使用 UXTU 时遇到任何问题或错误，请在我们的 [Discord 社区服务器](https://discord.gg/9FeYVcbbUQ) 中提出问题或联系 `@jamescj`、`@projectsbc` 或 `@sbski`。

如果您想通过捐赠支持 Universal x86 Tuning Utility 的开发，可以通过 [Patreon](https://www.patreon.com/uxtusoftware) 或 [PayPal](https://www.paypal.me/JamesCJ60) 进行捐赠。

## 什么是 UXTU？
- 这是一个旨在帮助您按照自己的意愿调整设备的调优工具。
- 它由 [Ryzen Controller](https://gitlab.com/ryzen-controller-team/ryzen-controller)、[Renoir Mobile Tuning](https://github.com/sbski/Renoir-Mobile-Tuning) 和 [Power Control Panel](https://github.com/project-sbc/Power-Control-Panel-v2) 的开发者创建。
- 它是一个轻量级的 Ryzen Master/XTU 替代品，适用于 x86 笔记本电脑和计算机，允许对设备的处理器和 GPU 进行精细控制。
- 在基于 Zen 的 CPU/APU 或第 4 代及更新的 Intel CPU 上效果最佳。

## 免责声明与注意事项
- 如果您打算在在线视频/文本帖子（例如 YouTube、Reddit）中使用 Universal x86 Tuning Utility，请通过链接到 Universal x86 Tuning Utility GitHub 发布页面来致谢 Universal x86 Tuning Utility 团队！我们这样要求是为了让观众/读者可以从可信来源下载软件，并让开发者得到应有的认可。
- Universal x86 Tuning Utility 团队不对使用 Universal x86 Tuning Utility 可能造成的任何损害承担责任。请自行承担使用风险！
- "AMD"、"APU"、"Ryzen" 和 "AMD Ryzen" 是 Advanced Micro Devices, Inc. 的商标。Universal x86 Tuning Utility 团队不声称拥有这些资产，仅将其用于信息目的。
- 如果您希望获得 Universal x86 Tuning Utility 的开发者访问权限，请在我们的 [Discord 社区服务器](https://discord.gg/9FeYVcbbUQ) 中联系 `@jamescj`、`@projectsbc` 或 `@sbski`。

## 安装
- 前往 [发布页面](https://github.com/JamesCJ60/Universal-x86-Tuning-Utility/releases)
- 点击下载链接
- 下载完成后，打开 .msi 安装程序并按照说明操作
- 应用程序现在应该已经安装完成
- 最后，在桌面上找到快捷方式并双击打开 UXTU
- UXTU 现在应该已经打开，尽情使用吧！！！

## 快速入门
_第一次使用 Universal x86 Tuning Utility？_ _不用担心！_ _本快速入门指南涵盖了开始使用所需的一切。_

#### 启动 UXTU
* 成功安装后，在桌面上找到 UXTU 图标并双击以启动应用程序。

#### 导航界面
* UXTU 界面有三个主要部分 - 预设预设、自定义预设和自适应模式。
* 这三个部分允许您按照自己的喜好调整设备。
* 其他部分包括游戏库、系统信息和自动化。

#### 预设预设
* Universal x86 Tuning Utility 提供专为基于 Zen 的处理器设计的预设预设。
* 这些预设是针对特定用例预配置的设置，提供便利和效率。
* 预设预设是自定义和实验的绝佳起点。
* 只需点击所需的预设即可将其应用到您的设备。

#### 自定义预设
* 自定义预设部分允许您创建高级调优配置。
* 根据您的系统，您可以根据自己的偏好修改各种设置。
* 配置完所需的设置后，可以选择应用它们和/或保存它们以备将来使用。
* 自定义预设提供高度的灵活性，允许用户定制设备的性能以满足特定需求。

#### 自适应模式
* UXTU 具有自适应模式，提供优化处理器性能的智能方法。
* 自适应模式实现了自适应 TDP（热设计功耗）算法，动态调整功率限制以在保持稳定性的同时优化性能。
* 通过持续监控处理器温度，自适应模式智能地平衡功率限制以实现最稳定的性能设置。
* 使用"启动自适应模式"按钮打开自适应模式，并根据您的偏好调整轮询率。

#### 其他部分
* 游戏库：查看和启动已安装的游戏。
* 系统信息：查看设备规格和信息。
* 自动化：选择在指定事件期间自动应用设置。

#### 成功调优的技巧
* 进行渐进式更改而不是剧烈更改，以保持稳定性和持久性。
* 注意硬件的推荐最高温度和 TDP。

## 使用的项目：
- [G-Helper (GitHub)](https://github.com/seerge/g-helper)  
- [WPF UI (GitHub)](https://github.com/lepoco/wpfui)
- [reverse_engineering (GitHub)](https://github.com/zllovesuki/reverse_engineering)  
- [Laptops (GitHub)](https://github.com/ahahahahahMtnf/Laptops/tree/main/Asus/WMI)  
- [ADLX SDK Wrapper (GitHub)](https://github.com/JamesCJ60/ADLX-SDK-Wrapper)
- [Magpie (GitHub)](https://github.com/Blinue/Magpie)
