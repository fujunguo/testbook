# 如何让程序「脱机运行」？

> makeblock 旗下的产品上传程序的方式都是类似的，唯一的区别就是——上传时记得选择好对应的主控板/控制板和串口，本文以入门级机器人 mBot 来讲解下整个过程。

1、[点击下载](http://www.mblock.cc/zh-home/software/mblock/mblock3/) PC 端软件 mBlock（如果你的电脑上没有安装的话）；

2、打开主板电源开关，用 USB 线将 mBot 连接至电脑，选择好对应的主控板：

![](../.gitbook/assets/image%20%2826%29.png)

3、选择好对应的串口

> 查看串口的方法可参考[如何查看「COM」口？](ru-he-cha-kan-zhu-ban-de-com-kou.md)

![](../.gitbook/assets/image%20%2812%29.png)

4、 串口连接成功后，软件界面左上角会显示「**串口 已连接**」字样，**此时可编写程序或打开网上下载的程序文件（.sb2后缀）**，我是自己编的一个程序：

![](../.gitbook/assets/image%20%2821%29.png)

5、右击「**mBot主程序**」，选择「**上传到Arduino**」

![](../.gitbook/assets/image%20%2822%29.png)

![](../.gitbook/assets/image%20%2825%29.png)

6、等到出现「**上传成功**」时，我们就成功将这个程序上传到了主控板，也就是可以实现这个程序的脱机运行了。

![](../.gitbook/assets/image%20%2811%29.png)

7、拔掉USB线，重启 mBot 看下程序运行效果。

