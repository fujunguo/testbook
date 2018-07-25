---
description: 一般我们提到的电机工作不正常，可能会有以下两种现象，下面针对不同问题现象给出解决方案。
---

# 005\_mBot 电机为何工作异常（走不直、方向反）？

#### 现象1：

给mBot发送前进指令时，小车做出后退的动作。

#### 解决方法：

多数情况是两个电机的接线插反了，在主板插口上将电机线对调即可。



#### 现象2：

给mBot发送前进或者后退的指令时，小车走的是曲线而非直线。

#### 解决方法：

1、可能轮子被 RJ25 线等物体卡住，检查两个轮子是否其中一个被螺丝拧得过紧，导致阻力变大，速度减慢。

2、可能轮胎安装没有到位，轮胎安装位置不正，会导致轮胎侧面接触地面，造成速度差导致转弯。

3、如排除第1、2步的原因，若小车依旧有轻微的不走直线，那是正常的。**因为在电机行业里，每个直流电机速度都有速度差异，这个可以通过后期软件编程解决，具体操作方法如下：**

在mBlock里面（**以下程序基于 mBlock3 编写, mBlock5 同理**）对小车进行编程矫正速度差：在程序上给两个电机设置不同的转速，可以让小车走直线。如在给同样的速度值（100）的时候，观察哪个电机的速度比较慢，然后就加大那个走得慢的电机的值，如电机1\(快\)速度= 100，电机2\(慢\)速度 = 105（如下图所示），然后将其上传至mBot，可以不断调节不同速度值，以达到两个电机同步的效果。

> 上传程序部分可参考[如何让程序「脱机运行」？](tips/ru-he-rang-cheng-xu-tuo-ji-yun-hang.md)

![](.gitbook/assets/mbot-dian-ji-wen-ti.png)
