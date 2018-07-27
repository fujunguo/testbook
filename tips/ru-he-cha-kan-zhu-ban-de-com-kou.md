# 如何查看主板的「COM口」？

> 在安装好 mBlock 软件后，我们想要让机器人和电脑通信（通过USB线或蓝牙适配器），这时候就需要用到「串口」（也就是我们常说的「COM口」，故后文均以「COM口」代替「串口」），那么该如何查看我们主控板对应的 COM 口呢？

下面介绍两种查看「COM口」的方式：

#### 方式一

用官方自带的 USB 线将机器人主控板连接至电脑，然后**打开主控板电源**，右击「**计算机**」选择「**管理**」，进入新窗口后选择「**设备管理器**」，你会看到「**端口**」下面有一些通信设备，有「**CH340**」或「**makeblock**」字样的 **COM3** 就是我们需要的东西（具体步骤可参考下图）：

![](../.gitbook/assets/image%20%2813%29.png)

#### 方式二

如果主控板电源开关也打开了、USB 线连接也没问题，而在「**设备管理器**」中还是未能发现我们想要的COM 口，**并且换个 USB 口还是不行的话**，这时候很大可能就是驱动程序的问题了，此时有两个办法可解决此问题：

1）点击 mBlock 里的「**安装 Arduino 驱动**」菜单，安装完成后重启 mBlock 程序以及重新插拔下 USB 线即可：

![](../.gitbook/assets/image%20%2831%29.png)

2）[点击](http://bbs.makeblock.com/forum.php?mod=attachment&aid=MzkwMXxiMzQ5ZDQxMnwxNDczMDkxMzYyfDg1Njd8MTEwNA%3D%3D)下载驱动文件（针对 Windows 系统），手动安装好驱动文件，装好后按照步骤1操作即可。Mac OS 可参考[这篇文档](http://www.mblock.cc/zh-home/docs/zh-run-makeblock-ch340-ch341-on-mac-os-sierra/)解决驱动文件问题。

