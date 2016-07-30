---
layout: post
title: "Raspberry Pi 2 Usage"
description: "树莓派使用感悟"
category: 
tags: [Raspberry]
---
# 树莓派的种类

## Raspberry Pi

## Raspberry Pi 2

## Raspberry Pi 3

最新版本，价格不错,升级了如下几个地方:

1. 价格
1. 内置WIFI模块
1. 内置蓝牙模块

不爽的地方:

1. 插入式TF卡，不再是弹出式TF卡槽，取卡换卡非常的费劲。
据说是由于弹出式卡槽成本，长时间弹出会出现松动的迹象

## Raspberry Pi Zero
1. 价格便宜到足够的量了，$5。
1. 小巧，没有网口
1. 接口规范
* 处理器: A Broadcom BCM2835 application processor 1GHz ARM11 core (40% faster than Raspberry Pi 1)
* 内存: 512MB of LPDDR2 SDRAM
* 尺寸: 65mm x 30mm x 5mm
* 接口：接口支持完全和以前的A, B, B+, 2 兼容. (微型SD卡槽, HDMI 视频口).

如下是官方规范

* A Broadcom BCM2835 application processor
* 1GHz ARM11 core (40% faster than Raspberry Pi 1)
* 512MB of LPDDR2 SDRAM
* A micro-SD card slot
* A mini-HDMI socket for 1080p60 video output
* Micro-USB sockets for data and power
* An unpopulated 40-pin GPIO header
* Identical pinout to Model A+/B+/2B
* An unpopulated composite video header
* Our smallest ever form factor, at 65mm x 30mm x 5mm

# 树莓派能够做什么

## 支持的OS
总体来说，树莓派就是一个低功耗的ARM系统，现在支持一下系统：

1. Linux
	1. **RaspBian**

		标准的RaspBerry Pi的Linux系统

	1. **Ubuntu**

		Ubuntu Mate

1. Windows 10(IOT版)

	支持基本的命令行，使用Visual Studio进行开发和调试，就不要想着跑Windows10的应用了。


## 多媒体中心

## 小巧的Linux服务器

### Git服务器
Gitlab已经提供了Raspbian的官方支持，直接安装开发包.deb即可。

### Web服务器

## 树莓派机群

基于TCP/IP，可以使用自带的100Mbps的网口进行通信，或者使用54Mbps的WIFI进行通信.

1. Openmpi

1. mpich2

	Raspbian中间自带，apt-get install mpich2

# 如何将树莓派应用好

---
{% include JB/setup %}
