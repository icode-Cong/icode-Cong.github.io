---
layout: post
title:  "Hungarian Algorithm（匈牙利算法）"
date:   2022-02-15 12:00:00
categories: coding4fun
tags: [algorithm]

---

匈牙利算法是一个经典的解决二部图最小权值匹配问题的算法。<!-- more -->


# 一、问题描述

有n个工作，需要指派给n个工人，每个工人完成每个工作的时间可能都不一样，给出一个算法，使得得到的指派结果总的时间最少。

图表示（$Wi$表示工人，$Ji$表示工作）：

![](D:\icode-Cong.github.io-master\img\Hungarian-1.png)

矩阵表示,其中矩阵的$（i,j）$元素值，代表第$i$个工人完成第$j$个工作的时间，称为权值矩阵。：

![](D:\icode-Cong.github.io-master\img\Hungarian-2.png)



# 二、记录

https://zhuanlan.zhihu.com/p/89380238

https://blog.csdn.net/u011837761/article/details/52058703