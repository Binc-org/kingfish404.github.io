---
layout: post
title: 计算机专业导论-周总结1-信息
date: 2019-11-21
categories: 计算机专业导论
tags: [专业导论]
description: 计算机知识，Computer Info
---

<!-- more -->
<!-- wp:paragraph -->
<p>记——11月14日夜在南湖学习的计算机科学导论 </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>这周学习了许多内容，包括且不限于计算机专业的方向，前景还有信息论等以前从未听说过的理论知识，感觉收获很多。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>上个星期 宋华珠老师 请了一位留学生来给我们进行讲课仍历历在目。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>我通过查阅资料，知道了计算机科学这个专业主要是做什么,未来的发展，下面是我找到的部分定义。</p>
<!-- /wp:paragraph -->

<!-- wp:quote -->
<blockquote class="wp-block-quote"><p> 计算机专业是指计算机硬件与软件相结合、面向系统、更偏向应用的宽口径专业。 理论性强，实践性强，通过基础教学与专业训练，培养基础知识扎实、知识面宽、工程实践能力强，具有开拓创新意识，在计算机科学与技术领域从事 科学研究 、教育、开发和应用的高级人才。 </p></blockquote>
<!-- /wp:quote -->

<!-- wp:paragraph -->
<p>这星期我们主要学习的是信息论，下面是我根据我所看书与和学长讨论了解到的知识对信息的内容进行的总结：</p>
<!-- /wp:paragraph -->

## 信息的定义：
1. 信息是认知主体对物质运动的本质特征、运动方式、运动状态以及运动的有序性的反映和揭示，是事物之间相互联系、相互作用的状态的描述。通俗地讲，信息泛指包含于消息、情报、指令、数据、图像、信号等形式之中的新的知识和内容。

2. 特征：普遍性、动态性、依附性、相对性、可传递性、共享性、可加工性。

3. 分类：  
    1. 按信息发生领域划分：物理信息、生物信息、社会信息  
    2. 人们对信息有无加工划分：原始信息、派生信息
    3. 按信息的表现形式划分：消息、资料、知识

## 信息熵计算公式：
![https://img-blog.csdnimg.cn/20191117173030525.png](https://img-blog.csdnimg.cn/20191117173030525.png)

<!-- wp:heading -->
<h2>信息的种类：</h2>
<!-- /wp:heading -->

<!-- wp:group -->
<div class="wp-block-group"><div class="wp-block-group__inner-container"><!-- wp:paragraph -->
<p>（1）按照产生信息的物体的性质，可以将信息分为自然信息（声、光、热、电等），生物信息（生物为繁衍生存而表现出来的各种形态和行为，如遗传信息、生物体内的交流信息、动物种群内的交流信息等），机器信息和社会信息等。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（2）按照人类活动领域，可以将信息分为科技信息、经济信息、政治信息、军事信息、文化信息等。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（3）按照信息所依附的载体，可以将信息分为文献信息、口头信息、电子信息、生物信息等。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（4）按照携带信息的信号性质，可以将信息分为连续信息、半连续信息和离散信息。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（5）按照信息所起的作用，可以将信息分为无用信息、有用信息和干扰信息。</p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:group -->

<!-- wp:heading -->
<h2><strong>位模式的信息表示</strong></h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>位模式是一个序列，有时也称为位串，它是0和1的组合。通常长度为8的位模式被称为1个字节(byte)，一个字由若干字节组成。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（1）文本的表示：文本格式的信息常用编码的方法来表示，文本中每一个不同的符号（如字母表中的字母或标点符号）被指定为一个唯一的位模式。这样，文本就被表示成一个长的位串，其中相应的位模式代表了原文中相应的符号。英文一般采用ASCII（America standard code for information
interchange）编码、Unicode编码等，而中文则大多采用与前者兼容的GB 2312-1980编码。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（2）数值的表示：以二进制形式存储数值。对于二进制而言，数据分为无符号数和有符号数（约定最高位为符号位，“1”表示负数，“0”表示正数）两类。又根据编码的不同，将其分为原码、补码、反码（正数的原码、补码、反码相同，负数的反码为其原码数值部分各位取反，补码为其原码除符号位以外各位变反加一）</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（3）音频的表示：要在计算机上表示音频信息，必须对声波进行数字化处理，即把模拟的声波转换成离散的数字信号。数字化处理的过程包括采样、量化和编码三个步骤。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（4）图像的表示：计算机处理图像有两种方式：矢量图和位图。在位图中，一个图像被看作是点的集合，每个点叫做像素。位图所需的存储容量较大。此外，缩放和旋转位图容易造成图像失真。矢量图是计算机图形学中用点、直线或者多边形等基于数学方程的几何图元表示的图像，它是根据客观事物而形成的。</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>（5）视频的表示：视频即运动图像，是指内容随时间变化的一组动态图像，它是由一幅接一幅的静止的图像组成的，也就是说，它由一系列帧组成。如果想保存一部25帧/秒、时长为90分钟、分辨率为1024*768、24位真彩色的电影，则需要大约296GB的存储空间。</p>
<!-- /wp:paragraph -->

## 计算机信息处理过程
（1）接收：信息接收包括信息感知、信息测量、信息识别、信息获取以及信息输入等。  

（2）存储：信息存储就是把计算机接收到的信息或计算机处理的中间信息通过存储设备进行缓冲、保存、备份等处理。  

（3）转化：信息转化就是将信息根据人们的特定需要进行分类、计算、分析、检索、管理和综合等处理。  

（4）传输：信息传输时通过计算机内部的指令或计算机之间的网络把信息从一个位置传送到另外一个位置。  

（5）发布：信息发布就是把信息通过各种表示形式展示出来。  


## 图灵机

1. 不是真实的机器，是一种理论模型。可以视为现代数学计算机的数学模型。

2. 图灵机有一个可以向左右两端无限伸展的纸带。有一个能在纸带上左右移动的读写头HEAD。还有一个控制器，存有控制规则和一个状态寄存器。

## 课堂问答

### 什么是信息？简单
	信息，指音讯、消息、通讯系统传输和处理的对象，泛指人类社会传播的一切内容。
	
	人通过获得、识别自然界和社会的不同信息来区别不同事物，得以认识和改造世界。
	
	在一切通讯和控制系统中，信息是一种普遍联系的形式。
	
	1948年，数学家香农在题为“通讯的数学理论”的论文中指出：“信息是用来消除随机不定性的东西”。创建一切宇宙万物的最基本单位是信息。

### 信息如何度量？
    信息一般通过信息熵来度量。
    离散型随机变量X~p（Xi）的信息熵是从平均意义上对信息不确定性的度量，也称为平均自信息量，定义为：
![https://img-blog.csdnimg.cn/20191117173030525.png](https://img-blog.csdnimg.cn/20191117173030525.png)  
    
	其中，随机变量X由n个事件Xi构成，事件Xi出现的概率为p(Xi )。

### 计算机中的信息以什么方式进行储存的？
    文本：文本格式的信息常用编码的方法来表示，文本中每一个不同的符号（如字母表中的字母或标点符号）被指定为一个唯一的位模式。这样，文本就被表示成一个长的位串，其中相应的位模式代表了原文中相应的符号。英文一般采用ASCII（America standard code for information interchange）编码、Unicode编码等，而中文则大多采用与前者兼容的GB 2312-1980编码。
    数值：以二进制形式存储数值。对于二进制而言，数据分为无符号数和有符号数（约定最高位为符号位，“1”表示负数，“0”表示正数）两类。又根据编码的不同，将其分为原码、补码、反码（正数的原码、补码、反码相同，负数的反码为其原码数值部分各位取反，补码为其原码除符号位以外各位变反加一）
    音频的表示：要在计算机上表示音频信息，必须对声波进行数字化处理，即把模拟的声波转换成离散的数字信号。数字化处理的过程包括采样、量化和编码三个步骤。
    图像：计算机处理图像有两种方式：矢量图和位图。在位图中，一个图像被看作是点的集合，每个点叫做像素。位图所需的存储容量较大。此外，缩放和旋转位图容易造成图像失真。矢量图是计算机图形学中用点、直线或者多边形等基于数学方程的几何图元表示的图像，它是根据客观事物而形成的。
    视频：视频即运动图像，是指内容随时间变化的一组动态图像，它是由一幅接一幅的静止的图像组成的，也就是说，它由一系列帧组成。如果想保存一部25帧/秒、时长为90分钟、分辨率为1024*768、24位真彩色的电影，则需要大约296GB的存储空间。

### 计算机可处理的信息有几种类型，分别是什么？
    四种，分别为：
    文本
    数值
    图像
    视频  

### 举例说明什么是信息处理？
    以个人博客中的博文为例进行说明：
    （1）接收：信息接收包括信息感知、信息测量、信息识别、信息获取以及信息输入等，用户通过标准输入设备如键盘鼠标等向计算机内输入信息。
    （2）存储：信息存储就是把计算机接收到的信息或计算机处理的中间信息通过存储设备进行缓冲、保存、备份等处理。计算机保存用户的输入。
    （3）转化：信息转化就是将信息根据人们的特定需要进行分类、计算、分析、检索、管理和综合等处理。将保存的信息转换为H5格式。
    （4）传输：信息传输时通过计算机内部的指令或计算机之间的网络把信息从一个位置传送到另外一个位置。将博文上传服务器
    （5）发布：信息发布就是把信息通过各种表示形式展示出来。在服务器发布。

### 简述什么是图灵机？
    图灵机模型是由英国数学家图灵提出的，是计算机的数学模型。
    所谓的图灵机就是指一个抽象的机器，它有一条无限长的纸带，纸带分成了一个一个的小方格，每个方格有不同的颜色。有一个机器头在纸带上移来移去。机器头有一组内部状态，还有一些固定的程序。在每个时刻，机器头都要从当前纸带上读入一个方格信息，然后结合自己的内部状态查找程序表，根据程序输出信息到纸带方格上，并转换自己的内部状态，然后进行移动。

### 什么是计算机科学？
    计算机科学（Computer Science, CS）是系统性研究信息与计算的理论基础以及它们在计算机系统中如何实现与应用的实用技术的学科。
    它通常被形容为对那些创造、描述以及转换信息的算法处理的系统研究。计算机科学包含很多分支领域；其中一些，比如计算机图形学强调特定结果的计算，而另外一些，比如计算复杂性理论是学习计算问题的性质。还有一些领域专注于挑战怎样实现计算。比如程序设计语言理论学习描述计算的方法，而程序设计是应用特定的程序设计语言解决特定的计算问题，人机交互则是专注于挑战怎样使计算机和计算变得有用、可用，以及随时随地为人所用。
现代计算机科学( Computer Science)包含理论计算机科学和应用计算机科学两大分支。

### 计算机学科的基本问题是什么？
    计算机科学的基本问题是：什么能（有效地）自动进行。



## 总结

<!-- wp:paragraph -->
<p>个人感觉，计算机专业所学习的程序的编写，主要就是为了处理各种各样的的数据，通过对信息的收集与处理，产生能够作用于实际生活并产生价值的信息。</p>
<!-- /wp:paragraph -->

## Reference
1. [Computer science-wiki](https://en.wikipedia.org/wiki/Computer_science)