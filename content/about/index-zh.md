## 关于我
我目前是美国伊利诺伊大学厄巴纳-香槟分校（UIUC）的在读研究生，专业是Autonomy & Robotics。 在加入 UIUC 之前，我是深圳渊联科技有限公司的自动驾驶汽车工程师。

我的研究兴趣是自动驾驶、运动规划和感知的交叉领域，其目标是通过智能决策系统和鲁棒感知系统来提高自动驾驶的智能性。

## 教育经历

- <p style="text-align:left;">
      <b>University of Illinois Urbana-Champaign (UIUC)</b> 
      <span style="float:right;">
          2022.08 - 2023.12 (预计毕业时间)
      </span>
  </p>


  - <p style="text-align:left;">
        专业： <b>M.Eng. in Autonomy & Robotics</b> 
        <span style="float:right;">
            厄巴纳, IL, USA
        </span>
    </p>

  - 当前课程：自动驾驶，机器学习，深度学习

- <p style="text-align:left;">
      <b>Northeastern University (NU)</b> 
      <span style="float:right;">
          2021.09 - 2022.05
      </span>
  </p>


  - <p style="text-align:left;">
        专业： <b>M.S. in Robotics (CS)</b> & Graduate Global Pathways (语言课程)
        <span style="float:right;">
            波士顿, MA, USA
        </span>
    </p>

  - Course: Robotics Science & System (Arm Motion Planning, EKF-SLAM, PCI, RANSAC Algorithm, etc.)

- <p style="text-align:left;">
      <b>Dongguan University of Technology (DGUT)</b> 
      <span style="float:right;">
          2015.09 - 2019.06
      </span>
  </p>


  - <p style="text-align:left;">
        专业： <b>机械设计制造及其自动化</b> 
        <span style="float:right;">
            东莞, China
        </span>
    </p>

  - 相关课程：机器人和机器视觉，线性代数，C/C++，理论力学等

## 工作经历

- <p style="text-align:left;">
      <b>自动驾驶工程师, 深圳渊联科技有限公司</b>
      <span style="float:right;">
          2020.7 - 2021.9
      </span>
  </p>


  - **地铁的自动刹车系统：** 基于欧几里得聚类算法对点云数据进行聚类、识别是否有人出现在地铁的轨道中，并依据此完成地铁的的自动刹车任务。 ([在深圳地铁中的测试](https://youtu.be/iXHDc-L6YHo))
  - **感知：** 同步处理不同激光雷达数据，融合拼接点云数据，减少车辆感知盲区； 实施 Pointpillars 算法和 Yolo3 来检测物体和人。
  - **自动驾驶系统架构：** 部署基于ROS的车辆和仿真（Gazebo）的感知、规划和决策模块； 开发用于测试和交互系统的 Android 应用程序和软件（基于 QT）。

- <p style="text-align:left;">
      <b>研究助理，东莞理工学院机械工程学院</b>
      <span style="float:right;">
          2019.7 - 2020.6
      </span>
  </p>


  - **工业机械臂故障诊断：** 使用基于水平的学习群优化器（LLSO）对极限学习机（ELM）的输入权重和隐藏层偏差进行优化，进一步提高极限学习机在齿轮故障工业机械臂故障诊断中的泛化性能（有裂纹， 断齿，点蚀）。 [[论文](https://journals.sagepub.com/doi/full/10.1177/16878140211019540)]
  - **群体智能:** 建立多头绒泡（一种粘菌）的觅食原理与群机器人系统的映射机制，设计仿生分布式搜索算法。 与其他搜索策略（包括一些从循环神经网络（RNN）训练的搜索策略）相比，所提出的算法提高了群机器人在有限通信环境下的适应性，并显示出更高的效率。 [[论文](https://www.hindawi.com/journals/complexity/2021/6698421/)]

## Project

<p style="text-align:left;">
    <font size=4><b>基于卷积神经网络 (CNN) 的赛博朋克 2077 自动驾驶系统</b>
    <span style="float:right;">
        2022.7 - 2022.8
        </span></font>
</p>

<div style="width:40%;">
	<img src="/img/cyberpunk1.jpg" style="float:left;"  height="300" width="300"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>车道线检测:</b> 根据霍夫变换计算图像中的直线，根据斜率和截距匹配相似的线组，取最常见的两条线段作为车辆的车道线。并基于Open CV实时绘出在游戏画面中。
    </p>
    <p style="padding-left: 45%;">
        <b>自动驾驶系统:</b> 收集每一时刻的键盘控制和图像帧作为输入，基于TFLearn训练的AlexNet深度卷积神经网络（CNN），使车辆通过学习玩家的操作数据完成自动驾驶任务。
    </p>
</div>

<p style="text-align:left;">
    <font size=4><b>Hybrid-Robotics, 拾取网球机器人</b>
    <span style="float:right;">
        2022.4 - 2022.5
        </span></font>
</p>

<div style="width:40%;">
	<img src="/img/locobot.jpg" style="float:left;" height="270" width="270"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>拾取:</b> 采集机器人的工作环境，并用于Cascade Classifier训练机器人对网球进行识别；根据Realsense传感器的摄像头矩阵计算网球到摄像头的距离真实距离，并将位置转换为机械臂的坐标系中； 基于 MoveIt API 通过RRT算法对拾取网球行为进行规划和执行。
    </p>
    <p style="padding-left: 45%;">
        <b>SLAM & Navigation:</b> 在机器人上基于Cartographer实现SLAM任务，并基于RRT算法的自主SLAM功能； 通过动态窗口算法 (DWA) 导航到放置网球的位置。（以上所有功能在Gazebo仿真和实际机器人中均有实现）
        <a href="https://github.com/Yandong-Luo/physical_locobot_ws">[Project Link]</a>
    </p>
</div>

<p style="text-align:left;">
    <font size=4><b>基于循环神经网络（RNN）的多机器人协作搜索系统</b>
    <span style="float:right;">
        2020.1 - 2020.2
        </span></font>
</p>

<div style="width:40%;">
	<img src="/img/rnn.gif" style="float:left;" height="210" width="200"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>端到端的强化学习:</b> 通过构建循环神经网络（RNN），结合遗传算法（GA）迭代训练多机器人系统学习相互协作，完成对目标的搜索。 根据时间消耗和机器人找到目标物体的次数构建了适应度函数。
    </p>
    <p style="padding-left: 45%;">
        <b>输入 & 输出:</b> 输入包括：群机器人LED灯颜色信号（群通信信号）、地板颜色识别信号（判断是否进入目标区域）、接近传感器检测到的距离和角度、 输出：差速轮的转速。
        <a href="https://github.com/Yandong-Luo/Multi-Robot-Search--RNN">[Project Link]</a>
    </p>
</div>

<p style="text-align:left;">
    <font size=4><b>基于极限学习机的工业机器人故障诊断</b>
    <span style="float:right;">
        2019.7 - 2020.6
        </span></font>
</p>



<div style="width:40%;">
	<img src="/img/Fault Diagnosis.jpg" style="float:left;" height="200" width="160"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Introduction:</b> 设计了一个带有基于级别的学习群优化器 (LLSO-ELM) 的极限学习机 (ELM)，用于对具有齿轮故障（包括裂纹、断齿、点蚀）的工业机械臂进行故障诊断。
    </p>
    <p style="padding-left: 45%;">
        <b>Implement:</b> 使用 LLSO 优化 ELM 的输入权重和隐藏层偏差，以进一步提高 ELM 的泛化性能。 将提出的 LLSO-ELM 与 ELM 进行比较，验证了 LLSO-ELM 的更高预测精度。
        <a href="https://journals.sagepub.com/doi/full/10.1177/16878140211019540">[Publication]</a>
    </p>
</div>

<p style="text-align:left;">
    <font size=4><b>仿多头绒泡觅食行为的群机器人目标搜索</b>
    <span style="float:right;">
        2022.4 - 2022.5
        </span></font>
</p>
<div style="width:40%;">
	<img src="/img/physarum_polycephalum.jpg" style="float:left;" height="230" width="230"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>目的:</b> 针对地震等自然灾难事故发生后人员搜救通信受限的问题，我启发于多头绒泡菌（一种黏菌）的觅食行为，设计了一种新颖的多机器人协同搜索策略。
    </p>
    <p style="padding-left: 45%;">
        <b>实现:</b> 与其他搜索策略（包括一些从循环神经网络（RNN）训练的搜索策略）相比，所提出的算法提高了群机器人在有限通信环境下的适应性，并显示出更高的效率。
        <a href="https://www.hindawi.com/journals/complexity/2021/6698421/">[Publication]</a>
    </p>
    <p style="padding-left: 45%;">
        <b>资助:</b> 获广东省教育厅20万资助。
    </p>
</div>

<p style="text-align:left;">
    <font size=4><b>土木建筑构件应力分析软件的开发</b>
    <span style="float:right;">
        2022.4 - 2022.5
        </span></font>
</p>

<div style="width:40%;">
	<img src="/img/qt.jpg" style="float:left;" height="230" width="290"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Purpose:</b> 与英国爱丁堡龙比亚大学的合作项目
    </p>
    <p style="padding-left: 45%;">
        <b>QT 开发:</b> 开发多种RS485传感器数据采集系统，包括倾角传感器、扭矩传感器、位移传感器； 涉及多线程、槽函数、串口开发、文件操作等。软件可支持16个传感器数据同时读取、数据存储、传输校验、高频读写等功能。
        <a href="https://github.com/Yandong-Luo/Datalog">[Project]</a>
    </p>
</div>


## 论文

- **Yandong Luo**, Jianwen Guo, Zhenpeng Lao, Shaohui Zhang, Xiaohui Yan, "Swarm Robot Exploration Strategy for Path Formation Tasks Inspired by *Physarum polycephalum*", *Complexity*, vol. 2021, Article ID 6698421, 17 pages, 2021. https://doi.org/10.1155/2021/6698421
- Guo, Jianwen, Xiaoyan Li, Zhenpeng Lao, **Yandong Luo**, Jiapeng Wu, and Shaohui Zhang. “Fault Diagnosis of Industrial Robot Reducer by an Extreme Learning Machine with a Level-Based Learning Swarm Optimizer.” Advances in Mechanical Engineering, (May 2021). https://doi.org/10.1177/16878140211019540.
- **Luo, Yandong**, Jianwen Guo, Guoliang Ye, Yan Wang, Li Xie, Xiang Wang, Shaohui Zhang, and Xiaohui Yan. “Toward Target Search Approach of Swarm Robotics in Limited Communication Environment Based on Robot Chains with Elimination Mechanism.” International Journal of Advanced Robotic Systems, (May 2020). https://doi.org/10.1177/1729881420919954.

## 奖项

1. 杨振宁奖学金
2. 第十五届挑战杯全国大学生课外学术科技作品竞赛三等奖 (项目负责人)
3. 广东省第四届“互联网+”大学生创新创业大赛银奖
4. 第六届“娃哈哈”全国大学生创业营销实践大赛第一名
5. 全国第十五届CaTICs网络赛（CAD，二维）三等奖（2016年12月）
6. 全国第十五届CaTICs网络赛（SolidWorks，三维）三等奖（2016年12月）
7. “莞工之星” ——"团队之星"
8. 三等奖学金
9. 学术奖学金
10. 优秀大学生
11. 优秀大学生

