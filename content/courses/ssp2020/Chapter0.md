---
title: "第0章 固体物理引论"
linktitle: Chapter 0
toc: true
type: docs
date: "2020-02-19T00:00:00+01:00"
draft: false
menu:
  ssp2020:
    parent: SSP2020
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---



## Introduction to Solid State Physics

**1.** 从**固体物理**到**凝聚态物理**：多学科交叉的物理学重要分支

+ 固体物理采用**量子力学**、**热力学与统计力学**等方法，从微观结构到宏观现象，研究具有一定刚度的物质（固体）的力学、热学、电磁学、动力学性质等。发展出了格波与声子理论、能带论、超导BCS理论、朗道-金兹堡对称破缺理论等重要方法和框架，极大拓展了人们对固体物质认识的广度和深度。
+ 固体与液体的主要区别是固体具有一定的剪切强度，而液体没有。通俗的说，固体具有一定的形状，而液体没有。固体和液体统称凝聚态，将液体、软物质等研究纳入研究领域，固体物理在80年代实现了跨越式学科发展，进入“凝聚态物理“时代。但凝聚态物理的核心和主体内容仍是固体物理（为什么？）。
+ 固体物理学的主要分支包括半导体、磁学、超导、表面物理等，固体物理的知识是材料工业、纳米科技、信息工业、能源工业等的基础和支撑，也是空间探测、量子计算等新兴技术的核心和重要基础。
+ [学科诞生记：凝聚态物理的兴起](https://swarma.org/?p=14933) (英文原文[Physics Today: When Condensed Matter Physics Became King](https://physicstoday.scitation.org/doi/pdf/10.1063/PT.3.4110))

****

**2. 涌现**（Emergence）及其物理：从原子到固体

+ 简明的固体模型：有序排列的原子，以电磁相互作用结合，形成固态物质。

+ 丰富的现象涌现：宏观尺度形形色色的固态性质，通过原子间的相互作用从微观尺度涌现出来。

+ 单晶体（single crystal）：原子规则排列“无限”延伸形成宏观大小的单晶体。完美的单晶不仅仅对称而美好，更是简明固体物理模型的理想实现（model material）。测量单晶材料的物理性质，可以最有效地验证固体物理的预言，单晶也常常能够理想地获得固态理论预言的优良材料性能。

+ | <img src="/courses/ssp2020/figs/quartz.jpg" style="zoom:60%;" name="square"/> | <img src="/courses/ssp2020/figs/cuso.jpg" style="zoom:59%;" name="square"/> |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 石英石单晶（天然）                                           | [五水合硫酸铜单晶（人工生长）](https://www.bilibili.com/video/av18581752/?spm_id_from=333.788.videocard.0) |

  人们最早就从单晶体碎裂后不同晶面夹角不变推断出晶体中的原子排列的有序性，推荐阅读：[晶体形貌与原子排列—阿羽衣的非凡一念（曹则贤）](https://chuansongme.com/n/1588175946319)

+ 固体简明的微观结构是否意味着具有简单的固体性质？

  + "由基本粒子构成的，巨大和复杂的集聚体的行为不能依据少数粒子的性质做简单外推就能理解。而正好相反，在复杂系统的每一个层次，都会呈现出全新的规律。而要理解这些新行为，所需要做的研究，就其基础性而言与其他研究相比毫不逊色。"
    + [P. Anderson—More is Different](/courses/ssp2020/refs/anderson1972.pdf) （[中译版](https://mp.weixin.qq.com/s/ie8yNAFmmNSviwdBGlkdXw)）
  + ”物理其实有两种不同的范式。长久以来，物理学家都在按“还原论”的范式，寻找拼成世界的那些最基本的“积木”以及它们遵循的规律，也取得了辉煌的成功。然而，这些却还不够，不同层次上还有不同的物理，“演生论”开始大展拳脚。” 
    + [物理世界话演生（向涛 院士）](https://www.bilibili.com/video/av90875778) 
    + [物理中的还原论与演生论](http://physics.buaa.edu.cn/info/1190/3497.htm)
  + 涌现物理：对称破缺与相变
    + [量子多体与相变（文小刚）](https://www.bilibili.com/video/av92533273?from=search&seid=9925950896848474010)

****

**3. 万物之理（Theory of Everything，ToE）**：原则上，通过求解固体模型的多体薛定谔方程，可以解释自然界中所有固态物质极其丰富的如力学、电磁学、热学性质等物理性质。

+ 多体相互作用的固态ToE的方程。求解多体量子力学薛定谔方程的困难程度和计算资源，随着研究对象规模的增长而指数增加，无法直接求解。需要通分离变量，采取恰当的近似求解得到相应的**固态理论**，如声子理论与电子能带理论等。

<img align='center' src='/courses/ssp2020/figs/ToE.png' width='700' hspace='24' />

+ **声子理论**：晶格离子实相互作用，振动在晶格中传播，形成格波，并激发能量量子——声子。提供了我们理解*反常固体比热*的重要量子图像，结合非谐效应并从而能够理解固体的热胀冷缩。
+ **能带理论**：通过波恩-奥本海默近似进一步简化ToE，将电子和离子实的运动分离开，电子运动在晶格离子实提供的周期电磁势场中，形成特殊的色散关系，即电子能带。电子能带理论提供了我们理解金属、绝缘体、半导体等提供了统一的*标准模型*。

****

**4.** 超越固体物理的“标准模型”框架

+ 以能带论、金兹堡-朗道平均场理论等为代表的固态理论构成我们理解物质世界形形色色的物态与材料的基本框架，类似于粒子物理中的“标准模型”。而量子霍尔效应、高温超导、拓扑磁性物态等新奇的发现则揭开了超越超越这个基本框架的“新物理”—关联多体物理，固体物理研究朝向非微扰、极端纠缠的量子物态新领域发展。
+ 固态物理学（solid state physics）— 凝聚态物理学（condensed matter physics）— **量子物态科学**（quantum matter science） 
+ 量子物态科学: 主要研究强烈关联和纠缠着的极端量子物质中涌现出的性质与规律。如量子霍尔效应中的拓扑序和任意子激发，新奇磁性状态与超导等。



****

## Slides & Video

+ Slides for Chapter 0 can be downloaded (please click the BIG icon below) 

  [![](/courses/ssp2020/figs/coverc0.png "Wei Li")](/courses/ssp2020/slides/slidesc0.pdf)

+ Video lecture (by Sandro Scandolo, ICTP), please click the icon below.

  [![Sandro Scandolo](/courses/ssp2020/figs/videoc0.png "Sandro Scandolo")](https://www.bilibili.com/video/av47845416?p=1)
  
+ [Notes by Shun-Yao Yu (Lecture 01)](/courses/ssp2020/notes/2020-02-07-P1.pdf).



****

## Discussions

+ An online discussion (c.a. 30 + 30 min, via Wechat or Dingtalk) will be arranged.



****

## Homework

+ 阅读P. Anderson的"More is different"一文。

+ 石英与玻璃的化学成分是什么？是什么将二者区分开来？

+ 自然界的单晶往往在何处能够找到? 请举3例你所熟悉的地球上天然形成的单晶物质。

+ Justification of *Bonn-Oppenheimer approximation*: Please estimate the electron speed orbiting ion (using *quantum mechanics*), and please compare it with the speed of ions. 

  

