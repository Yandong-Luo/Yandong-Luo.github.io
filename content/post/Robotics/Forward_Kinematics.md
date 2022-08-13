---
layout:     posts
title:      "机械臂正向运动学"
subtitle:   "Forward Kinematics of Robot Arm"
excerpt: "把机械臂关节变量作为自变量，描述机械臂末端执行器的位置和姿态与机械臂基座之间的函数关系"
author:     Yandong Luo
date:       2022-08-06
description: "把机械臂关节变量作为自变量，描述机械臂末端执行器的位置和姿态与机械臂基座之间的函数关系"
image: "/img/piano.jpg"
published: true 
markup: mmark
math: true
tags:
    - robotics
categories: [ Tech ]

---

## 机械臂正向运动

### DH建模

![DH](/img/Robotics_image/DH.png)

针对机械臂各个关节的姿态变化采用的是DH建模法。每个关节的都建立坐标系，而每个关节坐标系之间的关系便是通过DH的四个参数来确定，这四个参数分别是

- $a\_i$: 表示的是两个连杆i和i+1的z轴之间的距离，而这z轴的确定是与转动轴重合的
- $\alpha\_i$: 表示的是两个连杆i和i+1的z轴之间的角度
- $\theta\_{i+1}$: 表示的是两个连杆i和i+1的x轴之间的角度，x的方向是根据与a参数同向的方向来确定
- $d\_{i+1}$: 表示的是两个连杆i和i+1的x轴之间的距离

![four parameters](/img/Robotics_image/four_parameters.png)

#### 坐标转换

在确定了上面的四个参数后，其实我们可以已经计算出机械臂端的姿态在其他坐标系中的表达

![how to change](/img/Robotics_image/how_to_change.png)

这里以两个连杆的坐标系变换来解释

首先是设定i-1的关节首先绕x轴转动，转动$\alpha\_{i-1}$，这样使得Z轴与下一关节的Z轴平行，以此作为变换后的第一个坐标系R。

然后将这个坐标系平移$a\_{i-1}$距离，这样使得这个坐标系与下一关节的坐标系的Z轴重合了，该坐标系记为Q。

然后再将该坐标系绕Z轴旋转$\theta\_{i}$，使得X轴与关节i的方向平行，该坐标系记为P

然后再将该坐标系Q沿着Z轴方向移动$d\_{i}$移动到与X轴重合，至此，两个关节的坐标系就移动到位了

所以这两者的坐标系变换矩阵就是
$$
\begin{aligned}
^{i-1}P &=^{i-1}\_{R}T^R\_QT^P\_iT^iP\\\\
&=\left[\begin{matrix}cos\theta\_i & -sin\theta\_i & 0 & a\_{i-1}\\\\
sin\theta\_{i}cos{\alpha\_{i-1}}&cos\theta\_icos\alpha\_{i-1}&-sin\alpha\_{i-1}&-sin\alpha\_{i-1}d\_i\\\\
sin\theta\_{i}sin\alpha\_{i-1}&cos\theta\_isin\alpha\_{i-1}&cos\alpha\_{i-1}&cos\alpha\_{i-1}d\_i\\\\
0&0&0&1
\end{matrix}\right]
\end{aligned}
$$
