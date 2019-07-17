# OMEN by HP Laptop 15-ce0xx

### **👌The following is the content provided by Google Translate, which is inconvenient for you, please forgive me!**

### 😥There may be some problems with this EFI, use with caution！

<p><center>English(当前)|中文</center></p>

[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

![IMG_20190716_095724](C:\Users\YJL19\Documents\Tencent Files\631908942\FileRecv\MobileFile\IMG_20190716_095724.jpg)

### Configuration

| HP OMEN 3  | OMEN by HP Laptop 15-ce0xx                |
| ---------- | ----------------------------------------- |
| BIOS       | F.19-04/18/2019                           |
| CPU        | Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz |
| GPU        | NVIDIA GeForce GTX 1050                   |
| GPU        | Intel(R) HD Graphics 630                  |
| Sound card | ALC295                                    |
| Disk       | HP SSD EX950 512G、HGST 1T                |

### Normal function

- The sound card driver is normal, no broken sound is found.
- The configuration page is displayed normally.
- All functions are used normally, no error, including APP Store, ~~Facetime~~, iTunes, etc.
- The touchpad and battery are normal
- Normal sleep
- ~~Bluetooth has not been used, I don't know. . .~~
- On the machine ~ ~ all interfaces ~ ~ are normal, except the type-c interface has not been tried, I have no accessories for this interface
- The wired network card is normal, and the wireless network card has no solution.
- The original power supply is normal and the battery display is patches.
- Perfect to achieve unplugged boot (OMEN is the most difficult to solve this!)
- USB limitation, I don’t know if it’s released or not at all.[远景有篇帖子可以看看](http://bbs.pcbeta.com/viewthread-1804129-1-1.html)
- Wait a minute, not one by one!

### Invalid function

- ~~Small sun (brightness adjustment) is normal, patched~~ , can be adjusted at 10.13.6, need to be re-created separately at 10.14.5.
- FaceTime can be activated in 10.13.6 and below, and I can talk to my classmate's iPhone, but 10.14.5 is not working, I am still looking for the reason!
- Bluetooth needs to be activated separately (I have almost never used the Bluetooth of my laptop anyway, so I want to be lazy!)
- Type-c should not be used.
- Due to the well-known reasons, the wireless network card can not be driven, only rely on USB network card, wired network or a network card to solve, such as: Broadcom BCM94352z
- The keyboard can't adjust the brightness temporarily, so wait until you have time to manage it!
- It is impossible to drive the drop alone, everyone knows this!
- HDMI cannot be used because it can't be driven alone! There should be other solutions.
- Other problems have not been discovered for a while, or have not noticed. After all, everyone's use level is different. My requirement is to be able to simply entertain the office!

### Some reference tutorials

[黑苹果教程](http://www.zhuimeng.online/clover.html)

[HP暗影精灵3安装 macOS 10.14.3 Mojave 记录](https://mp.weixin.qq.com/s/oPAwyR9WafBcg0N-raPWYw)

[macOS Mojave黑苹果教程！](https://mp.weixin.qq.com/s/st7feN-yHfDcvCEngvbIEw)

[【黑果小兵】macOS Mojave 10.14.5 18F132 正式版 with Clover 4928原版镜像](https://blog.daliansky.net/macOS-Mojave-10.14.5-18F132-official-version-with-Clover-4928-original-image.html)

远景论坛[修改dsdt实现电量显示方法（整理修改已有帖子）](http://bbs.pcbeta.com/viewthread-1778499-1-1.html)

tonymacx86[HP OMEN 15-dc电池错误](https://www.tonymacx86.com/threads/solved-hp-omen-15-dc-battery-error.263814/#post-1841023)

[[指南]如何修补DSDT的工作电池状态](https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/)

### What can i do after installation?

远景论坛[黑苹果洗白成功分享](http://bbs.pcbeta.com/viewthread-1798846-1-1.html)

**[macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)**

### Download link Mirror sync upload

👍The image is from the blog of @黑果小兵's blog, and I use this image myself!

迅雷离线(BT)下载：[[请点击下载](https://mirrors.dtops.cc/iso/MacOS/daliansky_macos/macOS Mojave 10.14.5(18F132) Installer with Clover 4928.dmg)] 感谢`@难忘情怀`提供下载资源

http下载链接:[请点击下载](https://mirrors.dtops.cc/iso/MacOS/daliansky_macos/) 感谢`@难忘情怀`提供下载资源

百毒云：链接: <https://pan.baidu.com/s/1AKuzJXJe7haNYWo00YwJlQ> 提取码: ivmi

MD5 (macOS Mojave 10.14.5(18F132) Installer with Clover 4928.dmg) = 371d9145484beaf0795d6b7d0d569fc3

### Acknowledgement(thank、gratitude)

- 感谢 [Acidanthera](https://github.com/acidanthera) 提供 [AppleALC](https://github.com/acidanthera/AppleALC)，[HibernationFixup](https://github.com/acidanthera/HibernationFixup)，[Lilu](https://github.com/acidanthera/Lilu)，[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)，[VirtualSMC](https://github.com/acidanthera/VirtualSMC)，[VoodooPS2](https://github.com/acidanthera/VoodooPS2) 和 [WhateverGreen](https://github.com/acidanthera/WhateverGreen)。
- 感谢 [alexandred](https://github.com/alexandred) 提供 [VoodooI2C](https://github.com/alexandred/VoodooI2C)。
- 感谢 [apianti](https://sourceforge.net/u/apianti)，[blackosx](https://sourceforge.net/u/blackosx)，[blusseau](https://sourceforge.net/u/blusseau)，[dmazar](https://sourceforge.net/u/dmazar) 和 [slice2009](https://sourceforge.net/u/slice2009) 提供 [Clover](https://sourceforge.net/projects/cloverefiboot)。
- 感谢 [RehabMan](https://github.com/RehabMan) 提供 [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander)，[OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config)，[OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet)，[OS-X-USB-Inject-All](https://github.com/RehabMan/OS-X-USB-Inject-All) 和 [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext)。
- 感谢远景论坛的各位大佬提供的教程，以及[黑果小兵](https://github.com/daliansky)的镜像。

### Common problem

**Q:How to enter the BIOS or set the startup item?**

A:Press the ESC button after booting, then select according to the guidelines.

**Q:Do I need to log in to my Apple account?**

A:It is recommended to use the trumpet to log in, otherwise it may be blacked out by apple!

**Q:Why is it available on your computer, but not on my computer?**

A:I don't know, you can try to ask your computer: Why can't you?

**Q:Why is it so expensive?**

A:Google搜索:如何禁用独立显卡以节省电量

**Q:Why is there no HiDPI?**

A:I can't solve all the problems. If you can help me, I am so grateful to you!

### 🔊Solutions that speakers can't use

The sound card of Shadow Elves 3 is ALC295, find the `VoodooHDA-295.pkg` I provided in repo and install it. I am lazy, only provide this kind of solution, if you have a better plan, welcome to share!

### 😘Support me

| 微信                                                         | 支付宝                                                     |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ![mm_facetoface_collect_qrcode_1563329754957](C:\Users\YJL19\Desktop\mm_facetoface_collect_qrcode_1563329754957.png) | ![1563329762473](C:\Users\YJL19\Desktop\1563329762473.jpg) |

PayPal:https://www.paypal.me/bessyjl

### Contact me

Email:631908942#qq.com

微信公众号：爪哇派生