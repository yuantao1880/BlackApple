### 声明
本仓库的目的是出于兴趣收集一些常用机型的黑苹果EFI和工具。
#### 1.联想Y7000--clover引导
[参考博客](https://blog.csdn.net/bo_peter/article/details/104399269)
更改和兼容
1）驱动Intel的网卡：
[参考视频](https://www.bilibili.com/video/BV1iA411q7G4)
工具在文件中有
2）Windows与mac时间不同步的问题
在Windows系统下运行时间同步文件即可。
3）蓝牙和声卡均能正常驱动
4）bug右侧的数字小键盘不能使用。



#### 2.OC引导

假期比较头铁的直接升级到10.15.7结果系统崩了，于是试了好多个版本的OC都无法进入macOS中，在一个群里和一个大佬商量后出资￥20，在大佬的帮助下终于在oc引导下进入macOS

文件在oc中；

驱动网卡正常，右侧数字小键盘正常，声卡蓝牙……均正常；

不能正常休眠，推荐使用关闭屏幕代替休眠。



1.[如何添加Windows引导项](https://www.bilibili.com/video/BV1f541147Ag)

2.[如何对原生的WiFi进行驱动](https://www.bilibili.com/video/av245512419/)

对原生的WiFi进行驱动：

![](/img/wifi.png)



在Windows下成为黑苹果：

![](/img/1.png)

![](/img/2.png)