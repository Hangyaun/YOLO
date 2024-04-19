这个仓库记录yolo的学习过程和最终大作业的完成

yolo属于目标检测领域
目标检测的两大任务分别是目标在哪里和目标是什么

# CS231n课程笔记翻译：Python Numpy教程 - 知乎专栏



![](https://pic1.zhimg.com/56fe9d4b74ec164413a54bc57889c480_r.jpg)

[杜客][6] [Source](https://zhuanlan.zhihu.com/p/20878530?refer=intelligentunit "Permalink to CS231n课程笔记翻译：Python Numpy教程 - 知乎专栏")

**译者注**：本文[智能单元][1]首发，翻译自斯坦福CS231n课程笔记[Python Numpy Tutorial__][2]，由课程教师[Andrej Karpathy__][3]授权进行翻译。本篇教程由[杜客][4]翻译完成，[Flood Sung][5]、[SunisDown][6]、[巩子嘉][7]和一位不愿透露ID的知友对本翻译亦有贡献。

  

## 原文如下

这篇教程由[Justin Johnson__][8]创作。

我们将使用Python编程语言来完成本课程的所有作业。Python是一门伟大的通用编程语言，在一些常用库（numpy, scipy, matplotlib）的帮助下，它又会变成一个强大的科学计算环境。

我们期望你们中大多数人对于Python语言和Numpy库比较熟悉，而对于没有Python经验的同学，这篇教程可以帮助你们快速了解Python编程环境和如何使用Python作为科学计算工具。

一部分同学对于Matlab有一定经验。对于这部分同学，我们推荐阅读 [numpy for Matlab users__][9]页面。

你们还可以查看[本教程的IPython notebook版__][10]。该教程是由[Volodymyr Kuleshov__][11]和[Isaac Caswell__][12]为课程[CS 228__][13]创建的。

内容列表：

* Python
    * 基本数据类型
    * 容器
    * 函数
    * 类
