---
layout:     post
title:      "从零开始安装 Windows"
subtitle:   "以后装机不求人"
date:       2016-12-06 12:00:00
author:     "Aaron"
header-img: "img/hero.gif"
tags:
    - windows
    - 系统安装
    - 小白向
---

## 程序猿的苦衷

> "你是程序员嘛(✧◡✧)"  
"是哒(｡･ω･｡)"  
"那你可以修好我的修电脑嘛(๑•̀ㅂ•́)و✧"  
"卒。。。"

## 前言

每次融入一个新的~~[麻瓜](https://zh.wikipedia.org/wiki/%E9%BA%BB%E7%93%9C)~~圈子，说起自己是程序程序猿，基本都会发生这样的情况,对于程序猿来说这很尴尬。

这就是为什么我要写这篇博客  
~~以后有人问就直接把我博客的链接一扔，不仅可以化解尴尬，还能顺便装一逼,一举两得~~

# 开始
---

#### 准备材料

- 一台硬件正常的计算机  ~~不正常的先砸电脑，再看下面的文章~~
- 4G以上的U盘  
或微软官网购买 USB Flash Driver
- 网络连接 ~~没有网络的可以用手机开热点~~

## 获取 Windows 安装镜像
这里我提供了多种途径，适合各种不同情况的同学(仅限非大陆用户)

#### 从微软官网购买正版 Windows 10

[点我](https://www.microsoft.com/en-us/windows/get-windows-10)进入微软官网

你有 Windows 10 Home 和 Windows 10 Pro 两种选择
关于两个版本的区别，可以参考[维基百科](https://zh.wikipedia.org/zh-cn/Windows_10%E7%89%88%E6%9C%AC%E5%88%97%E8%A1%A8)上的说明

- 懒于思考觉得电脑能用能打游戏就好的可以直接无脑购买 [Home](https://www.microsoftstore.com/store/msusa/en_US/pdp/Windows-10-Home/productID.319937100?ICID=Windows_Win10Home_ModE) 版
- 需要硬盘加密和远程桌面等功能的则购买 [Pro](https://www.microsoftstore.com/store/msusa/en_US/pdp/Windows-10-Pro/productID.319935900?ICID=Windows_Win10Pro_ModE) 版  
~~常念微软大法好，Home版就会变成Pro版啦~~~

在微软官方商城上购买 Download 的，直接下载  
若购买 USB Flash Driver 的，则直接跳过制作U盘安装器的过程

#### 从第三方网站获取 Windows 10 安装镜像
选择此选项可以安装**正版**和**盗版**Windows  
*按照本博客的方法安装，盗版和正版在实际用上没有任何差别，就看你有没有支持正版的心*  
~~常念微软大法好，盗版会变成正版哦~~

#### 从[windowsiso.net](http://windowsiso.net/)下载

- 本教程适合所以 Windows 7 及以上的版本，你可以选择下载其他版本的 Windows 进行安装
- Windows 10 N 和 Windows 10 KN 并不建议大家安装，具体原因你可以去问[谷歌娘](https://www.google.com/)
- 请下载 **X64** 版本 X64比X86性能更强，具体问万能的[谷歌娘](https://www.google.com/)
~~十年高龄老爷机请选择X86~~
- 本教程适用于各种语言版的 Windows ,你可以自由的选择系统语言(安装后可更改)

## 制作可移动安装介质
*就是U盘启动器啦*

#### 下载可引导USB闪存盘制作工具 [Rufs](https://rufus.akeo.ie/)
~~悄悄提醒一下，蓝色的字都是不能按下去的(´；ω；`)~~


#### 写入镜像到U盘
此操作会清除U盘**所有数据**

打开软件，选择你的U盘

然后点击文件夹图标，像这样

![img](/img/windows/w1.png)

这里选择你刚刚下载好的镜像文件

打开下载好的镜像，点击**Start**按钮

（**U盘中的数据将会全部被清除**，做好备份，千万不要备份到正要重装系统的这台电脑！）

出现任何选项全部选是

进度条走完以后，Windows安装介质就制作完成了

## 从安装介质启动

#### BIOS 设置

首先你需要知道自己电脑进入 BIOS 的按钮是什么  
一般来讲，当你按下开机按钮后的第一个画面上都会有显示的  
没有的话，可以点击[这里](https://www.google.com)(在天朝按[这里](https://www.baidu.com))，然后你知道要怎么做了

在 **BIOS** 的 **Boot** 选项中将你的U盘移动至第一位，然后保存并重启，安装程序便启动了，接下来只要一直无脑点确定就行了！
