---
layout: post
title: 计算机专业导论-周总结3-硬件与网络
date: 2019-12-01
categories: 计算机专业导论
tags: [专业导论]
description: 计算机知识，Computer Info
---


## 计算机硬件
<!-- more -->### 移动终端

> 移动终端是指能够执行与无线接口上的传输有关的所有功能的终端装置。

它包括的范围很广，如果按照工作原理划分，可以分为模拟移动终端和数字移动终端，如模拟蜂窝手机和数字蜂窝手机；如果按应用领域区分，可以分为公众网移动终端和专业网移动终端，如GSM手机、CDMA手机、寻呼机等属于公众网移动终端。

但是，尽管大量通信终端厂家和芯片厂商涌入各种不同的移动终端领域，最为重要的移动终端主要还是手机这种公众网移动终端，即手机终端。

## 计算机网络

![NETWORK](https://www.runoob.com/images/pic_web.jpg)

计算机网络系统就是利用通信设备和线路将地理位置不同、功能独立的多个计算机系统互联起来，以功能完善的网络软件实现网络中资源共享和信息传递的系统。

通过计算机的互联，实现计算机之间的通信，从而实现计算机系统之间的信息、软件和设备资源的共享以及协同工作等功能，其本质特征在于提供计算机之间的各类资源的高度共享，实现便捷地交流信息和交换思想。

### 计算机网络组成

构成计算机网络系统的要素 :

* <b>计算机系统</b>:工作站(终端设备，或称客户机，通常是PC机)、网络服务器(通常都是高性能计算机)。

* <b>网络通信设备</b>(网络交换设备、互连设备和传输设备):包括网卡、网线、集线器(HUB)、交换机、路由器等。

* <b>网络外部设备</b>:如高性能打印机、大容量硬盘等

* <b>网络软件</b>:包括网络操作系统，如Unix、NetWare、Windows NT等;客户连接软件(包括基于DOS、Windows、Unix操作系统的等);网络管理软件等。

### 计算机网络分类

> 按信息类型分

* 电话通信系统
* 数据通信系统
* 有线电视系统

> 按调制方式分

* 基带传输
* 调制传输

> 按传输信号特征分
* 模拟通信系统
* 数字通信系统

### 计算机网络硬件组成

1. 网络传输媒体
 传输媒体(Transmission Medium) 也称传输介质或传输媒介，它就是数据传输系统中在发 送器和接收器之间的物理通路。它可分为两大类，即导向传输媒体和非导向传输媒体。在导向传输媒体中，电磁波被导向沿着固体媒体（铜线或光纤）传播，而非导向传输媒体就是指自由空间，在非导向传输媒体中电磁波的传输常称为无线传播。网络传输媒介的质量的好坏会影响数据传输的质量，包括速率、数据丢包等。

2. 中继器
 中继器（RP repeater）是工作在物理层上的连接设备。适用于完全相同的两类网络的互连，主要功能是通过对数据信号的重新发送或者转发，来扩大网络传输的距离。 中继器是对信号进行再生和还原的网络设备：OSI模型的物理层设备。

3. 集线器
 集线器的英文称为“Hub”。“Hub”是“中心”的意思，集线器的主要功能是对接收到的信号进行再生整形放大，以扩大网络的传输距离，同时把所有节点集中在以它为中心的节点上。它工作于OSI(开放系统互联参考模型)参考模型第一层，即“物理层”。

     集线器与网卡、网线等传输介质一样，属于局域网中的基础设备，采用CSMA/CD（即带冲突检测的载波监听多路访问技术)介质访问控制机制。集线器每个接口简单的收发比特，收到1就转发1，收到0就转发0，不进行碰撞检测。

4. 交换机
 交换机（Switch）意为“开关”是一种用于电（光）信号转发的网络设备。它可以为接入交换机的任意两个网络节点提供独享的电信号通路。最常见的交换机是以太网交换机。其他常见的还有电话语音交换机、光纤交换机等。

5. 路由器
 路由器是连接两个或多个网络的硬件设备，在网络间起网关的作用，是读取每一个数据包中的地址然后决定如何传送的专用智能性的网络设备。
 路由器能够理解不同的协议，例如某个局域网使用的以太网协议，因特网使用的TCP/IP协议。这样，路由器可以分析各种不同类型网络传来的数据包的目的地址，把非TCP/IP网络的地址转换成TCP/IP地址，或者反之；再根据选定的路由算法把各数据包按最佳路线传送到指定位置。所以路由器可以把非TCP/ IP网络连接到因特网上。

### 计算机网络拓扑结构

    总线型拓扑结构

    星型拓扑结构

    环形拓扑结构

    树形拓扑结构

### 计算机网络体系结构

1. OSI参考模型

![OSI](https://static.runoob.com/images/mix/v2-854e3df8ea850c977c30cb1deb1f64db_r.jpg)

2. TCP/IP参考模型

![TCP/IP](https://gss1.bdstatic.com/9vo3dSag_xI4khGkpoWK1HF6hhy/baike/c0%3Dbaike80%2C5%2C5%2C80%2C26/sign=c8e9fbafd2a20cf4529df68d17602053/80cb39dbb6fd5266417d403ca918972bd4073647.jpg)

3. 计算机网络协议
![协议](https://www.runoob.com/wp-content/uploads/2018/09/1538030297-3401-20150904094424185-2018280216.gif)

## 云计算

### 云计算概述

    云计算本质上是一种共享服务。

云计算（cloud computing）是分布式计算的一种，指的是通过网络“云”将巨大的数据计算处理程序分解成无数个小程序，然后，通过多部服务器组成的系统进行处理和分析这些小程序得到结果并返回给用户。

云计算早期，简单地说，就是简单的分布式计算，解决任务分发，并进行计算结果的合并。因而，云计算又称为网格计算。通过这项技术，可以在很短的时间内（几秒种）完成对数以万计的数据的处理，从而达到强大的网络服务。

    

### 云计算架构

![yun](https://gss3.bdstatic.com/-Po3dSag_xI4khGkpoWK1HF6hhy/baike/crop%3D0%2C28%2C793%2C523%3Bc0%3Dbaike92%2C5%2C5%2C92%2C30/sign=0bbb8c57afefce1bfe64928a9261dfec/bd315c6034a85edf16e5318241540923dd547522.jpg)

## 物联网
### 物联网简介

>物联网(The Internet of Things)的概念是在1999年提出的，它的定义很简单：把所有物品通过射频识别等信息传感设备与互联网连接起来，实现智能化识别和管理。物联网通过智能感知、识别技术与普适计算、泛在网络的融合应用，被称为继计算机、互联网之后世界信息产业发展的第三次浪潮。

物联网被视为互联网的应用拓展，应用创新是物联网发展的核心，以用户体验为核心的创新2.0是物联网发展的灵魂。


### 物联网的特征
* 全面感知,即利用RFID,传感器,二维码等随时随地获取物体的信息;

* 可靠传递,通过各种电信网络与互联网的融合,将物体的信息实时准确地传递出去;

* 智能处理,利用云计算,模糊识别等各种智能计算技术,对海量的数据和信息进行分析和处理,对物体实施智能化的控制。

### 物联网的体系结构

目前，物联网还没有一个被广泛认同的体系结构，但是，我们可以根据物联网对信息感知、传输、处理的过程将其划分为三层结构，即感知层、网络层和应用层，具体体系结构下图所示。  

![物联网结构](https://wiki.mbalib.com/w/images/3/33/%E7%89%A9%E8%81%94%E7%BD%91%E4%BD%93%E7%B3%BB%E7%BB%93%E6%9E%84.jpg)

## Reference

1. [中国物联网](http://www.iotcn.org.cn/)
2. [物联网 - MBA智库百科](https://wiki.mbalib.com/wiki/%E7%89%A9%E8%81%94%E7%BD%91)
3. [计算机网络基础知识总结\|菜鸟教程](https://www.runoob.com/w3cnote/summary-of-network.html)
4. [云计算_百度百科](https://baike.baidu.com/item/%E4%BA%91%E8%AE%A1%E7%AE%97/9969353?fr=aladdin)
5. 童玲.计算机网络硬件建设及其维护[J].电脑编程技巧与维护,2018(07):169-170+173.
6. 提高计算机网络可靠性的方法研究[J]. 张晓杰,姜同敏,王晓峰. ] 计算机工程与设计. 2010(05)
7. [TCP/IP参考模型_百度百科](https://baike.baidu.com/item/TCP%2FIP%E5%8F%82%E8%80%83%E6%A8%A1%E5%9E%8B)
8. [云计算架构_百度百科](https://baike.baidu.com/item/%E4%BA%91%E8%AE%A1%E7%AE%97%E6%9E%B6%E6%9E%84/766857?fr=aladdin)