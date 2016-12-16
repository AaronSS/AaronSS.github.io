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

## 获取 Windows 10 安装镜像
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

#### 懒人一键下载

都已经懒到如这种度了，说明什么的也你不想看了，那你一定会喜欢这种简单~~粗♂暴~~的方式

**中文版**  
```
https://software-download.microsoft.com/pr/Win10_1607_Chinese(Simplified)_x64.iso?t=a416b633-7402-4d2a-a9d3-af772874e0ed&e=1481149901&h=289084f046ff9973de097fbfc95c636d
```

**英文版**  
```
https://software-download.microsoft.com/pr/Win10_1607_EnglishInternational_x64.iso?t=62cecda0-f22e-4a22-b20d-3eef1a877f76&e=1481149911&h=a5f408f20cae41dcf39a22c432af799c
```

## 制作可移动安装介质
*就是U盘启动器啦*

#### 下载安装 [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/files/latest/download)

安装过程略。。。  
~~脑补我已经很详细地写在这里了~~

#### 写入镜像到U盘
此操作会清除U盘**所有数据**

先插上U盘，再打开刚刚安装好的程序

程序默认是选择了U盘的，可以在Device选项更改

然后点击文件夹图标，像这样(我的截图没有插U盘)

![img](/img/windows/w1.png)

然后在文件类型那选择所有文件类型，就像这样

![img](/img/windows/w2.png)

打开下载好的镜像，点击**Write**按钮  
进度条走完以后，Windows安装介质就制作完成了

# 我居然没写完就交上来了\_(:3」∠)\_
