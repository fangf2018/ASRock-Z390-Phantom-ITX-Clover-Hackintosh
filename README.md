# ASRock-Z390-Phantom-ITX-Clover-Hackintosh

# 更新日志

2019-10-3
* 增加一个1.6版本的bios 已更改为苹果启动logo 可直接刷入 参考[修改教程](https://www.bilibili.com/read/cv2788822/)

* 主logo

    ![2](http://github.fangf.cc/2019-10-03-2.jpg)
    
* 右下角文字

    ![IMG_8883](http://github.fangf.cc/2019-10-03-IMG_8883.JPG)

## 配置

主板：华擎z390 phantom gaming-itx/ac

cpu：i7 9700k

显卡：amd 蓝宝石 rx480

网卡：BCM943602CS


## BIOS设置

Advanced \ Chipset Configuration → Vt-d : Disabled

Advanced \ Super IO Configuration → Serial Port: Disabled

Advanced \ USB Configuration → XHCI Hand-off : Enabled

Advanced \ Chipset Configuration → Share Memory : 128MB

Advanced \ Chipset Configuration → IGPU Multi-Monitor : Enabled


# 参考
[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)

[macOS Catalina 10.15安装中常见的问题及解决方法](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html)

[使用HIDPI解决睡眠唤醒黑屏、花屏及连接外部显示器的正确姿势](https://blog.daliansky.net/Use-HIDPI-to-solve-sleep-wake-up-black-screen,-Huaping-and-connect-the-external-monitor-the-correct-posture.html)

[OpenCore部件补丁](https://github.com/daliansky/OC-little)


# 感谢
**[daliansky](https://github.com/daliansky)（黑果小兵）**

**[RehabMan](https://bitbucket.org/RehabMan/)**

**[ZeRo° Xu](https://github.com/xzhih)(冰水加劲Q)**

**[acidanthera](https://github.com/acidanthera/OpenCorePkg)**

**[Bat.bat](https://github.com/williambj1)**