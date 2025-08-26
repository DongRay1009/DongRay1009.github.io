---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

🌟**Welcome to My Page!**🌟

I spent three years at Beijing University of Chemical Technology, majoring in Mechanical Design and Automation. Currently, I’m a senior at the University of Detroit Mercy (UDM), pursuing a Bachelor's degree in Robotics and Mechatronics. 


<span style="color: red;">I am actively looking for research and intern opportunities in robotics and machine learning.</span>

# 🔥 News
- *2025.05*：&nbsp;We won first prize at robocup@home 2025!🎇🎉🍾

- *2024.07*: &nbsp;Such a pleasure that I can have the opportunity to intern at STATE GRID INTELLIGENCE TECHNOLOGY CO.,LTD

  

# 📝 Projects
~: Equal Contribution
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Lerobot</div><img src='images/Lerobot.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Reproducing and Training the ACT Neural Network from the LeRobot Project**](https://www.bilibili.com/video/BV1u3kmYFEzM/?share_source=copy_web&vd_source=1d11b082e214e205bf1127f07df592b2)

*Team Members: [**Jiawei Xia~**](https://harroldx.github.io/maplex.github.io/)*, **Xianglei Dong~**

- The robotic arm involved in the project was 3d printed as well as physically assembled. We also attempted to train the dataset ourselves to allow the robotic arm to autonomously organize the desktop

- Set up the project environment and dependencies, including configuring frameworks. Conducted in-depth research on the ACT algorithm from the LeRobot project, implemented and reproduced its core functionalities based on the original paper. Designed and executed training pipelines, monitored performance metrics, and conducted multiple experiments to validate results against the paper’s benchmarks. Debugged training issues (e.g., gradient vanishing and hyperparameter tuning) and optimized model performance.



</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RoboCup</div><img src='images/RoboCup.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**RoboCup@Home China Open 2024**](https://www.bilibili.com/video/BV1Yw4m1S7pn/?share_source=copy_web&vd_source=1d11b082e214e205bf1127f07df592b2)

*Team Members: [**Jiawei Xia**](https://harroldx.github.io/maplex.github.io/)*, **Xianglei Dong**, *Wengcong Zhang, Boyi Zhang, Yutong Sun*

- Developed an intelligent home service robot using Kinova Gen2 and Kinect Azure camera, with functions including guest reception and guidance, voice interaction, object recognition, and room cleaning
- Used the End-to-end grasping algorithm Graspnet to obtain the 6D pose of the object, which will be sent to the end of the robotic arm by 'TF listener, Controlled the arm using Actionlib and Movelt!, used the RR'T* algorithm for efficient trajectory generation, and TRAC-IK for an accurate inverse kinematics solver. Adopted Azure Al Speech SDK for speech recognition and voice output, combined with a finite state machine to enable simple human-computer voice interaction. For object recognition, integrated YOLOv8 3d detection and Kinect DK. Applied Cartographer for 2D indoor mapping, used IRIS LaMa for robot localization, achieved local path planning based on the DWA and global path planning based on the A* algorithm



</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RoboMaster</div><img src='images/RM_sim2real.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ICRA RoboMaster University Sim2real Challenge 2024**](https://www.bilibili.com/video/BV1ugbKeaEhx/?share_source=copy_web&vd_source=1d11b082e214e205bf1127f07df592b2)

*Team Members: [**Jiawei Xia**](https://harroldx.github.io/maplex.github.io/), **Xianglei Dong**, *Wengcong Zhang, Boyi Zhang*

- ICRA 2024 RoboMaster University Sim2Real Challenge: Utilized ArUco markers to determine the poses of boxes. Extracted the transformation and rotation matrices of boxes from detected marker poses. Deployed an Extended Kalman Filter (EKF) alongside an omnidirectional robot to enhance localization and pose estimation accuracy.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">rviz plugin</div><img src='images/waypoint_nav_plugin.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [**Waypoint_nav_plugin**](https://github.com/DongRay1009/waypoint_nav_plugin)

*Team Members: **Xianglei Dong***

- Implemented functionality for outputting waypoints to a `waypoints.txt` file.

- Enabled multi-point navigation for robots, significantly reducing the need for manual input of coordinate points in RViz.

- Contributed to the improvement of robot path planning and navigation efficiency.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">graspnet</div><img src='images/graspnet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [**YOLOv8 GraspNet ROS**](https://github.com/DongRay1009/yolov8_graspnet_ros)

*Team Members: **Xianglei Dong***

- An integrated ROS (Robot Operating System) based system combining YOLOv8 target detection and GraspNet grasping pose generation, mainly for robot visual grasping tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">yolo 3d detection</div><img src='images/yolo_3d_detection.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [**Yolov8 3d detection based on ROS**](https://github.com/DongRay1009/yolov8_3d_ros)

*Team Members: **Xianglei Dong***

- Based on ROS Noetic, YOLO 3D Detection is a real-time 3D target detection technology based on YOLO (You Only Look Once) series of target detection algorithms, designed for autonomous driving, robot navigation and other scenarios, and is able to predict the 3D Bounding Box and spatial attitude of an object from 2D images or point cloud data.

</div>
</div>

# 🏅 Honors and Awards
- *2025.05* The First Prize, RoboCup@Home China Open
- *2024.11* The Second Prize, ICAN International Contest of innovAtioN
- *2024.05* The Second Prize, RoboCup@Home China Open
  


# 📖 Educations

- 2022.09 - now, B.Eng., Mechanical Design, Manufacturing, and Its Automation, Beijing University of Chemical Technology. Beijing, China

# 💻 Internships

- *2024.07 - 2024.09*, [Hardware and software engineer], STATE GRID INTELLIGENCE TECHNOLOGY CO.,LTD, Jinan, Shandong. 

# 📄 CV
- [CV](https://github.com/DongRay1009/DongRay1009.github.io/blob/main/Dong_CV.pdf)

