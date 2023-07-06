#  NUC9代 幽灵峡谷/石英峡谷

支持全系列CPU型号，E-2286M、i9-9980HK、i7-9750H、i5-9300H

# 主机测评视频，淘宝店铺：小明白工作室

更新引导至OC094版本 可支持新版MacOS，包含Catalina、big sur、Monterey、Ventura、Sonoma

# 相关链接
说明指南： https://www.bilibili.com/read/cv24729831

https://www.bilibili.com/video/BV1em4y1c71M

https://www.bilibili.com/video/BV1mz4y1d75a/

油管 https://www.youtube.com/watch?v=RngHQqNjHTA&t=16s

# NUC9i5/i7/i9QNX、NUC9VXQNX  MacOS 完善程度

CPU正常睿频（i5/i7/i9/E2286M）

核显支持HDMI/Tyepc-c显示输出

前后USB所有正常使用

SD卡槽正常使用

前后3.5音频输出皆正常

睡眠唤醒正常，支持USB唤醒

雷电支持热插拔，可支持接显示器、接雷电硬盘

有线网卡i219正常使用，I210不建议开启

板载intel AX200 蓝牙 和WIFi都可以驱动，网速非常不错 ，但不支持隔空随航；MacOS 14需搭配heliport APP使用WIFI功能

若想实现隔空随航附加功能 需要买一张NVME M.2 SSD转接黑果无线网卡

引导默认可支持独显（RX560/570/590/5500/5600/5700/6600系列）

没有独显仅使用核显，需修改引导的IGPU-config.plist为config.plist使用

作者：小明和他的女朋友 https://www.bilibili.com/read/cv24729831 出处：bilibili

![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/Sonoma.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/Ventura.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/TB3.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/TB3-SN750.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/音频.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/WIFI6.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/BT.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/雷电接显示器.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/HDMI2.0.png)
![](https://github.com/Xmingbai/NUC9-hackintosh-i5-i7-i9QNX-NUC9VXQNX-hackintosh/blob/main/有线网口.png)

# 若有其他问题请加Q群：608352460，备注小明或者B站

# 也欢迎关注B站：小明和他的女朋友

#bios 设置参考

Internal graphics >enable

Security

Intel Platform Trust Technology: Unchecked

Intel Software Guard Extension (SGX): Disabled

Thunderbold Security Level: Legacy mode

Boot

Secure Boot: Disabled

Fast Boot: Unchecked


