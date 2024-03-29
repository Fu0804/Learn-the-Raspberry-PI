# Learn-the-Raspberry-PI
How I learn Raspberry PI from 0

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/76c0cd8b-544d-408d-a7ca-46866a1045f0">
</div>

## 树莓派简介
树莓派是一个可以运行Linux操作系统的微型开发板计算机，由英国树莓派基金会开发，用来在英国和发展中国家促进学校的基础计算机科学教育。其软件兼容各类Linux发行版。麻雀虽小，五脏俱全。物联网、人工智能、大数据、信息安全、web开发等等均有其应用平台。

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/31ed0d3c-8046-4535-95ac-e5e202fcbc40">
</div>

支持各类编程语言，例如python、linux、java，以及一些可视化编程。
### 2G/4G/8G区别
2G：图形化界面网上冲浪、部署微型服务器、微型显示屏观看视频等  
4G：复杂多任务处理、深度学习图像处理等  
8G：64位系统可以匹配8G，更好发挥CPU性能等
### 4B较3B+升级
主CPU升级，性能提升三倍以上，支持双HDMI输出，蓝牙升级为5，USB接口升级为USB3.0。务必使用5V/3A对树莓派进行供电。散热很重要。
## 树莓派如何开机
### 软件准备
1、烧写工具、内存卡修复工具

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/676f0580-7937-4251-9a22-59d87e32c8a3">
</div>

2、树莓派4B镜像操作系统（初学者镜像或官方镜像）

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/15489ca6-3938-4fab-b68b-bf4f76b25a67">
</div>

注：初学者镜像商家配置了很多功能
### 硬件准备
散热装备、SD卡、烧录镜像读卡器、5V/3A充电线、HDMI线、一台电脑显示

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/9e2d5381-8d0a-41ba-b7f7-79da503193e8">
</div>

### 烧录镜像
1、将SD卡插入读卡器中  
2、将读卡器插入电脑中  
3、提示需要格式化  

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/c3a5e57a-4db0-4365-9356-8e4c221f7407">
</div>

4、打开内存修复工具并将内存卡格式化

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/7b07aaf9-dd8e-472b-b5d1-17c47130a5cc">
</div>

可能会格式化失败，多试几次就可以。  
5、打开烧录软件

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/93a701e4-3f66-4b1b-9dca-9c9c4990c7e8">
</div>

6、选中镜像软件  
注：镜像软件以.img结尾(记得解压缩)

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/93b3b0fd-8eb7-44a3-ac66-5ab6f458e4ac">
</div>

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/8752ef02-ba95-4732-a1b4-fbd092dbf9a9">
</div>

7、点击烧写write

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/ee5db8e1-6b9f-4df7-ac20-7e067c93b668">
</div>

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/5d9c3763-9a7a-4c8a-86fa-cf875866b1f3">
</div>

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/9fcd1310-1f1f-44e1-9ac0-79504635a13b">
</div>

进度条满格后会显示烧写成功。点击OK即可。  
同时还会提示将光盘格式化。  
* 注意！！！千万不能格式化！  

烧录镜像后会发现盘空间系统变小。这是由于其数据格式转变为linux系统下格式，在windows系统下是看不出它的真实内存的。  
8、拔出读卡器U盘并装到树莓派上
### 树莓派开机
1、将内存卡插入底部卡槽

<div align=center>
<img src="https://github.com/Fu0804/Learn-the-Raspberry-PI/assets/151499353/90281f14-1c9c-45fc-8592-d3240e447baa">
</div>

2、连接屏幕HDMI线、电源线、鼠标及键盘、散热片或散热风扇  
3、连接WiFi（直接点击图形化界面WiFi图标即可连接）
