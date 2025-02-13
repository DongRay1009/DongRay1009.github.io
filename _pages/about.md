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

I am an undergraduate student at Beijing University of Chemical Technology, where I am leading as a member of SIE Robotics Club, a student organization focusing on robotics competitions.

<span style="color: red;">I am actively looking for research and intern opportunities in robotics and machine learning.</span>

# 🔥 News

- *2024.07*: &nbsp;Such a pleasure that I can have the opportunity to intern at STATE GRID INTELLIGENCE TECHNOLOGY CO.,LTD

  

# 📝 Projects
*: Equal Contribution
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Lerobot</div><img src='images/Lerobot.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Reproducing and Training the ACT Neural Network from the LeRobot Project**

*Team Members: Jiawei Xia*, **Xianglei Dong**

- The robotic arm involved in the project was 3d printed as well as physically assembled. We also attempted to train the dataset ourselves to allow the robotic arm to autonomously organize the desktop

- Set up the project environment and dependencies, including configuring frameworks. Conducted in-depth research on the ACT algorithm from the LeRobot project, implemented and reproduced its core functionalities based on the original paper. Designed and executed training pipelines, monitored performance metrics, and conducted multiple experiments to validate results against the paper’s benchmarks. Debugged training issues (e.g., gradient vanishing and hyperparameter tuning) and optimized model performance.



</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RoboCup</div><img src='images/RoboCup.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboCup@Home China Open 2024**

*Team Members: Jiawei Xia, Xianglei Dong, Wengcong Zhang, Boyi Zhang, Yutong Sun*

- Developed an intelligent home service robot using Kinova Gen2 and Kinect Azure camera, with functions including guest reception and guidance, voice interaction, object recognition, and room cleaning
- Used the End-to-end grasping algorithm Graspnet to obtain the 6D pose of the object, which will be sent to the end of the robotic arm by 'TF listener, Controlled the arm using Actionlib and Movelt!, used the RR'T* algorithm for efficient trajectory generation, and TRAC-IK for an accurate inverse kinematics solver. Adopted Azure Al Speech SDK for speech recognition and voice output, combined with a finite state machine to enable simple human-computer voice interaction. For object recognition, integrated YOLOv5 and Kinect DK. Applied Cartographer for 2D indoor mapping, used IRIS LaMa for robot localization, achieved local path planning based on the DWA and global path planning based on the A* algorithm



</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RoboMaster</div><img src='images/RM_sim2real.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ICRA RoboMaster University Sim2real Challenge 2024**

*Team Members: Jiawei Xia, Xianglei Dong, Wengcong Zhang, Boyi Zhang*

- ICRA 2024 RoboMaster University Sim2Real Challenge: Utilized ArUco markers to determine the poses of boxes. Extracted the transformation and rotation matrices of boxes from detected marker poses. Deployed an Extended Kalman Filter (EKF) alongside an omnidirectional robot to enhance localization and pose estimation accuracy.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">rviz plugin</div><img src='images/swarm.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 **Waypoint_nav_plugin** 

*Team Members: Xianglei Dong*

- Implemented functionality for outputting waypoints to a `waypoints.txt` file.

- Enabled multi-point navigation for robots, significantly reducing the need for manual input of coordinate points in RViz.

- Contributed to the improvement of robot path planning and navigation efficiency.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">graspnet</div><img src='images/graspnet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 **Updates to the graspnet-baseline** 

*Team Members: Xianglei Dong*

- Adjustments to the graspnet code to accommodate newer versions of the torch for compilation and runtime

</div>
</div>

# 🏅 Honors and Awards

- *2024.11* The Second Prize, ICAN International Contest of innovAtioN
- *2024.05* The Second Prize, RoboCup@Home China Open
  
  

# 📖 Educations

- 2022.09 - now, B.Eng., Mechanical Design, Manufacturing, and Its Automation, Beijing University of Chemical Technology. Beijing, China

# 💻 Internships

- *2024.07 - 2024.08*, [Hardware and software engineer], STATE GRID INTELLIGENCE TECHNOLOGY CO.,LTD, Jinan, Shandong. 

# 📄 CV
- [CV](https://github.com/DongRay1009/DongRay1009.github.io/blob/main/Dong_CV.pdf)

