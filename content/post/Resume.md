---
layout:     page
title:      "About Me"
subtitle:   "Having an absolute passion for driving, but committed to L5 Autopilot development"
description: "I am currently a M.Eng. candidate for Autonomy & Robotics at University of Illinois Urbana-Champaign (UIUC). Before joining UIUC, I was a Self-driving Car Engineer at Shenzhen Yelink Technology Co., Ltd."
excerpt: "I am currently a M.Eng. candidate for Autonomy & Robotics at University of Illinois Urbana-Champaign (UIUC). Before joining UIUC, I was a Self-driving Car Engineer at Shenzhen Yelink Technology Co., Ltd."
date:       2022-08-08
author:     "Yandong Luo"
image:      "/img/car7.jpg"

multilingual: true
---

## About Me

I am currently a M.Eng. candidate for Autonomy & Robotics at University of Illinois Urbana-Champaign (UIUC). Before joining UIUC, I was a Self-driving Car Engineer at Shenzhen Yelink Technology Co., Ltd.

My research interests are in the intersection of autonomous driving, motion planning, and perception, whose goal is to improve the intelligence of autonomous driving by intelligent decision systems and robust perception systems.

## Education

- <p style="text-align:left;">
      <b>University of Illinois Urbana-Champaign (UIUC)</b> 
      <span style="float:right;">
          2022.08 - 2023.12 (Expected)
      </span>
  </p>

  - <p style="text-align:left;">
        Candidate for <b>M.Eng. in Autonomy & Robotics</b> 
        <span style="float:right;">
            Urbana, IL, USA
        </span>
    </p>

  - Current Courses: Autonomous Vehicle System Engineering, Deep Learning, Machine Learning

- <p style="text-align:left;">
      <b>Northeastern University (NU)</b> 
      <span style="float:right;">
          2021.09 - 2022.05
      </span>
  </p>

  - <p style="text-align:left;">
        Candidate for <b>M.S. in Robotics (CS)</b> & Graduate Global Pathways (language program)
        <span style="float:right;">
            Boston, MA, USA
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
        Candidate for <b>B.Eng. Mechanical Engineering and Automation</b> (with IEET Accreditation) 
        <span style="float:right;">
            Dongguan, China
        </span>
    </p>

  - Related Courses: Robotics and Machine Vision, Linear Algebra, C/C++, Theoretical Mechanics, etc.

## Professional Experience

- <p style="text-align:left;">
      <b>Self-driving Car Engineer (L4 Self-driving Car), Shenzhen YeLink Technology Co., Ltd.</b>
      <span style="float:right;">
          2020.7 - 2021.9
      </span>
  </p>
  
  - **Autonomous Braking System for Train:** Based on the Euclidean clustering algorithm to identify the people appearing in the tunnel, and then finished the autonomous braking task. ([Tested in trains in Shenzhen](https://youtu.be/iXHDc-L6YHo))
  - **Perception:** Synchronous processing of different Lidar data, fusing and Splicing point cloud data to reduce the perception blind spot of vehicles; Implement Pointpillars algorithms and Yolo3 to detect objects and person.
  - **Autonomous Driving System Architecture:** Deploy the perception, planning, and decision modules of vehicles and Simulation (Gazebo) based on ROS; Develop Android apps and software (based on QT) for testing and interacting the systems.

- <p style="text-align:left;">
      <b>Research Assistant, Guangdong Intelligent Equipment Engineering Research Center</b>
      <span style="float:right;">
          2019.7 - 2020.6
      </span>
  </p>

  - **Fault Diagnosis of Industrial Robots:** Used the level-based learning swarm optimizer (LLSO) to optimize the input weights and hidden layer biases of the Extreme Learning Machine (ELM) to further improve the generalization performance of ELM for fault diagnosis of industrial robotic arms with gear failures (with crack, broken tooth, pitting). [[Publication](https://journals.sagepub.com/doi/full/10.1177/16878140211019540)]
  - **Swarm Robotics:** Setting up the mapping mechanism between the foraging driving principle of physarum polycephalum (a slime mold)
    and the swarm robot system to design a bio-inspired distributed search algorithm. The proposed algorithm improved the adaptability of swarm robots in limited communication circumstances and shows more efficiency when compared with other search strategies, including some search strategies trained from the Recurrent Neural Network (RNN). [[Publication](https://www.hindawi.com/journals/complexity/2021/6698421/)]

## Project
<p style="text-align:left;">
    <font size=4><b>Autopilot on Cyberpunk 2077 Based on Convolutional Neural Network (CNN)</b>
    <span style="float:right;">
        2022.7 - 2022.8
        </span></font>
</p>

<div style="width:40%;">
	<img src="/img/cyberpunk1.jpg" style="float:left;" />
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Lane Line Detection:</b> Calculate the straight lines in the image based on Hough transform, and match similar line groups based on slope and intercept, and take the two most common line segments as the lane lines of the vehicle.
    </p>
    <p style="padding-left: 45%;">
        <b>Autopilot:</b> Collecting the keyboard control and the frame of image, the AlexNet deep Convolutional Neural Network (CNN) based on TFLearn is trained, so that the vehicle can complete the automatic driving task.
    </p>
</div>

<p style="text-align:left;">
    <font size=4><b>Hybrid-Robotics, Autonomous Tennis Ball Collector</b>
    <span style="float:right;">
        2022.4 - 2022.5
        </span></font>
</p>
<div style="width:40%;">
	<img src="/img/locobot.jpg" style="float:left;" height="300" width="300"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Pick up Function:</b> Training the robot to recognize tennis balls based on Cascade Classifier; Calculating the distance of tennis balls from the camera based on the camera matrix of the Realsense sensor and converting the position to the frame of the arm; Based on MoveIt API to pick up the tennis ball.
    </p>
    <p style="padding-left: 45%;">
        <b>SLAM & Navigation:</b> Implement Cartography-SLAM on robot and develop an RRT-autonomous SLAM function; Navigating to where the tennis ball is placed through a dynamic window algorithm (DWA).
        <a href="https://github.com/Yandong-Luo/physical_locobot_ws">[Project Link]</a>
    </p>
</div>


<p style="text-align:left;">
    <font size=4><b>Multi-Robot Collaborative Search Based on Recurrent Neural Network (RNN)</b>
    <span style="float:right;">
        2020.2 - 2020.3
        </span></font>
</p>


<div style="width:40%;">
	<img src="/img/rnn.gif" style="float:left;" height="300" width="330"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>End-to-End Learning:</b> By constructing a recurrent neural network (RNN), combined with genetic algorithm (GA) to iteratively train multi-robot system to learn to cooperate with each other and complete the search for targets. Built a fitness function based on the time consumption and the number of times the robot finds target objects.
    </p>
    <p style="padding-left: 45%;">
        <b>Input & Output:</b> The input includes: the color signal of the LED lights of the group robot (group communication signal), the signal of the floor color recognition (judging whether to enter the target area), the distance and angle detected by the proximity sensor, and the output: the rotational speed of the differential wheel.
        <a href="https://github.com/Yandong-Luo/Multi-Robot-Search--RNN">[Project Link]</a>
    </p>
</div>
<p style="text-align:left;">
    <font size=4><b>Fault Diagnosis of Industrial Robots by an Extreme Learning Machine</b>
    <span style="float:right;">
        2019.7 - 2020.6
        </span></font>
</p>




<div style="width:40%;">
	<img src="/img/Fault Diagnosis.jpg" style="float:left;" height="200" width="250"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Introduction:</b> Designed an extreme learning machine (ELMs) with a level-based learning swarm optimizer (LLSO-ELM) for fault diagnosis of industrial robotic arms with gear failures, (including crack, broken tooth, pitting).
    </p>
    <p style="padding-left: 45%;">
        <b>Implement:</b> Used the LLSO to optimize the input weights and hidden layer biases of the ELMs to further improve the
generalization performance of ELMs. Compared the proposed LLSO-ELM with the ELM that verified the higher prediction accuracy of LLSO-ELM.
        <a href="https://journals.sagepub.com/doi/full/10.1177/16878140211019540">[Publication]</a>
    </p>
</div>
<p style="text-align:left;">
    <font size=4><b>Target Search of Swarm Robot Imitating the Foraging Behavior of Physarum Polycephalum</b>
    <span style="float:right;">
        2019.7 - 2020.6
        </span></font>
</p>
<div style="width:40%;">
	<img src="/img/physarum_polycephalum.jpg" style="float:left;" height="300" width="300"/>
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Purpose:</b> In response to the limited communication in personnel search and rescue after earthquakes, I designed a novel multi-robot cooperative search strategy inspired by the foraging behavior of Phyllodes polycephalus (a slime mold).
    </p>
    <p style="padding-left: 45%;">
        <b>Implement:</b> The proposed algorithm improved the adaptability of swarm robots in limited communication circumstances and shows more efficiency when compared with other search strategies, including some search strategies trained from the Recurrent Neural Network (RNN).
        <a href="https://www.hindawi.com/journals/complexity/2021/6698421/">[Publication]</a>
    </p>
    <p style="padding-left: 45%;">
        <b>Funding:</b> 200,000 RMB funded by Guangdong Provincial Department of Education.
    </p>
</div>


<p style="text-align:left;">
    <font size=4><b>Development of Stress Analysis Software for Civil Construction Components</b>
    <span style="float:right;">
        2021.2 - 2021.3
        </span></font>
</p>

<div style="width:40%;">
	<img src="/img/qt.jpg" style="float:left;" />
</div>
<div style="width:100%;">
	<p style="padding-left: 45%;">
        <b>Purpose:</b> Collaborative project with Edinburgh Napier University, UK.
    </p>
    <p style="padding-left: 45%;">
        <b>QT Development:</b> Develop a variety of RS485 sensor data acquisition systems, including inclination sensors, torque sensors, displacement sensors; involving multi-threading, slot function, serial port development, file operation, etc. The software can support the simultaneous reading of 16 sensor data, data storage, transmission verification, high-frequency reading and writing and other functions.
        <a href="https://github.com/Yandong-Luo/Datalog">[Project]</a>
    </p>
</div>

## Selected Publication

- **Yandong Luo**, Jianwen Guo, Zhenpeng Lao, Shaohui Zhang, Xiaohui Yan, "Swarm Robot Exploration Strategy for Path Formation Tasks Inspired by *Physarum polycephalum*", *Complexity*, vol. 2021, Article ID 6698421, 17 pages, 2021. https://doi.org/10.1155/2021/6698421
- Guo, Jianwen, Xiaoyan Li, Zhenpeng Lao, **Yandong Luo**, Jiapeng Wu, and Shaohui Zhang. “Fault Diagnosis of Industrial Robot Reducer by an Extreme Learning Machine with a Level-Based Learning Swarm Optimizer.” Advances in Mechanical Engineering, (May 2021). https://doi.org/10.1177/16878140211019540.
- **Luo, Yandong**, Jianwen Guo, Guoliang Ye, Yan Wang, Li Xie, Xiang Wang, Shaohui Zhang, and Xiaohui Yan. “Toward Target Search Approach of Swarm Robotics in Limited Communication Environment Based on Robot Chains with Elimination Mechanism.” International Journal of Advanced Robotic Systems, (May 2020). https://doi.org/10.1177/1729881420919954.

## Awards

1. Yang Chen-Ning Scholarship (Yang Chen-Ning, Nobel Laureate in Physics in 1957)
2. Third prize in the “15th ‘Challenge Cup’ National University Students’ Extracurricular
    Academic Science and Technology Works Competition” (the highest achievement of school,
    457/1229 in China)
3. First prize in the “14th ‘Challenge Cup’ Guangdong University Students’ Extracurricular
    Academic Science and Technology Works Competition” (the highest achievement of school,
    117/1123 in Guangdong Province)
4. Silver Award of the 4th “Internet+” Innovation and Entrepreneurship Competition for
    University Students in Guangdong Province (the highest achievement of school, 25/120 in
    Guangdong Province)
5. First Prize in the 6th “WaHaHa” National University Student Entrepreneurship Marketing
    Practice Competition (the highest achievement of school)
6. Third Prize in 15th National Computer-Aided Team & Individual Challenges (2D, CAD)
    12/2016
7. Third Prize in 15th National Computer-Aided Team & Individual Challenges (3D,
    SolidWorks) 12/2016
8. Special Awards in the 7th “Challenge Cup” College Students Extracurricular Academic
    Science and Technology Competition, Dongguan University of Technology (Scientific and
    Technological Inventions Group) 09/2017
9. Third Prize in the 7th “Challenge Cup” College Students Extracurricular Academic Science
    and Technology Competition, Dongguan University of Technology (Academic Papers Group)
    09/2017
10. “Guangong Star” ——"Team Star", Dongguan University of Technology 05/2018
11. Third-class Scholarship, Dongguan University of Technology 10/2016
12. Academic Scholarships, Dongguan University of Technology 10/2017
13. Outstanding Students, Dongguan University of Technology 12/2017
14. Academic Scholarships, Dongguan University of Technology 10/2018
15. Excellent graduates, Dongguan University of Technology 06/2019

## Feedback

If you find any problems or have some interest in these projects, please feel free to let me know that: dongdashu.aa@gmail.com

