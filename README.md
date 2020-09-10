# Mecanum-based-on-k210
An open NCUT laboratory project
## 设计目标

1. 机器视觉相关算法和程序设计，对于目标进行识别与跟踪，实现对于活动物体（比如人类或者小车）的跟踪。

2. 智能小车的控制算法，掌握麦克纳姆轮的控制方法并利用PID法尽可能的加快小车的速度响应

3. 人机交互程序，通过人工控制来干预小车的运动，同时返回速度、方向等基本参数，拟设计一套无线调参和一套无线图传系统

4. 造车技术，通过绘制PCB，3D打印等方式，优化小车的稳定性、集成度、外观等。

## 核心部件

1. k210![image-20200902185546935](C:\Users\41448\AppData\Roaming\Typora\typora-user-images\image-20200902185546935.png)

一款比较有"想象力"的MCU，自主研发，RISC-V架构，主频400MHz，巅峰1Tops的算力。

外设基本满足我们的需求

2. 麦克纳姆轮

![【学渣的自我修养】麦克纳姆轮浅谈](https://pic4.zhimg.com/7e655e2421da64a088a64585b2761cb5_1440w.jpg?source=172ae18b)

![img](https://pic1.zhimg.com/80/693092f7ca548af79d2eff49aa04be4c_720w.jpg)

这是关于[麦克纳姆轮小车](https://zhuanlan.zhihu.com/p/20282234 "Title") 相关文档的链接。

麦克纳姆轮是一种非常有趣的装置，可以在不调转车头的情况下进行全向的运动，它有非常鲜明的缺点，它价格高，不耐磨损，各个方向的力矩都有损耗，但是在智能小车领域，它依旧拥有很高的地位，我们在制造的过程中，尽可能规避一些缺陷，把优点充分的发挥出来。
