# 001\_mBot为何连不上手机蓝牙？

如果遇到mBot始终连接不上手机蓝牙的问题，有以下几种可能：

#### 1、购买的是非蓝牙版 {#1-gou-mai-de-shi-fei-lan-ya-ban}

购买的是 2.4G 版的mBot（**2.4G 模块无法实现蓝牙连接**），而非蓝牙版本 mBot，如果是这种情况的话，可以另行购买一个蓝牙模块，即可实现机器人跟手机蓝牙通信。下图左边是 2.4G 模块，右图为蓝牙模块：2.4G 模块和蓝牙模块

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHm2NO_uWcdNf68KaXB%2F-LHm2t-j2QBgx3AKA9km%2F-LHm3tNCHVLjtB8AaV2U%2Fimage.png?alt=media&token=6845fa9e-2d39-4e1d-aa5a-2dc9e3eae95e)

> 2.4G模块的用法可参考[002\_2.4G 版本的 mBot 如何使用？](https://fujun-guo.gitbook.io/mbot/0022.4g-ban-ben-de-mbot-ru-he-shi-yong)​

#### 2、电池电量不足 {#2-dian-chi-dian-liang-bu-zu}

如果是电池电量太低的话，主板上电后蓝牙模块的蓝色LED灯会快速地闪烁，可**拔掉**电池盒的接头，直接用USB线连接电脑后连接蓝牙（**USB供电足以给蓝牙模块供电**）以验证是否是该问题。

#### 3、上传过其他程序 {#3-shang-chuan-guo-qi-ta-cheng-xu}

在电脑上的mBlock里上传了自己编写的程序，可参考﻿﻿[如何「恢复出厂程序」？](https://fujun-guo.gitbook.io/mbot/tips/ru-he-hui-fu-chu-chang-cheng-xu)﻿﻿ 操作后重新连接蓝牙。

#### 4、蓝牙模块损坏 {#4-lan-ya-mo-kuai-sun-huai}

如果蓝牙模块的蓝色LED灯在主控板上电后一直保持常亮（**正常是刚开始上电后间缓缓闪烁，连接好手机蓝牙后它才会一直保持常亮**），那么可断定该蓝牙模块已损坏。

