---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV as PDF]({{ base_path }}/files/cv.pdf)

Education
======
* Doctor of Mechatronic Engineering, Huazhong University of Science and Technology, Wuhan, Hubei, China, Sept. 2020 - expected June 2026
  * Dissertation: Research on Methods for Improving Contour Accuracy in Robotic Milling of Complex Deep-Cavity Casing
  * Supervisors: Prof. Jixiang Yang and Prof. Han Ding
* Bachelor of Mechanical Design and Manufacturing Engineering, Central South University, Changsha, Hunan, China, Sept. 2016 - June 2020

Research Profile
======
My research centers on solving the bottleneck of high-precision robotic milling for large-scale aerospace components. Working at the intersection of robot dynamics, machine learning, and control engineering, I develop methods to improve robotic contour accuracy under extreme dynamic conditions.

Core competencies include:
* Robot dynamics and process optimization
* Intelligent error compensation and vision fusion
* System integration and hardware innovation for active vibration suppression

Skills
======
* Programming languages: Python, C++, MATLAB, PyTorch
* Software: ROS, UG, SolidWorks, Linux
* Hardware platforms: KUKA, ABB, and UR industrial robots; force and acceleration sensors; laser trackers

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Conferences
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Patents
======
Co-inventor (student first inventor) of five Chinese national invention patents focused on robotic precision manufacturing, adaptive vibration suppression, and digital twin systems.

* Jixiang Yang, Shizhong Tan, and Han Ding. Offline joint error compensation method, system, and terminal for gravity pose decomposition of industrial robots. Chinese Invention Patent No. CN114131611B, Granted.
* Jixiang Yang, Shizhong Tan, and Han Ding. Optimization method of tool orientation and redundancy angles in robotic ball-end milling. Chinese Invention Patent No. CN117908466B, Granted.
* Jixiang Yang, Shizhong Tan, and Han Ding. Active vibration suppression method and system for robotic milling considering pose-dependent modal dynamics. Chinese Invention Patent No. CN118700153B, Granted.
* Jixiang Yang, Shizhong Tan, and Han Ding. Decoupling control method and system for a two-degree-of-freedom robotic vibration suppressor. Chinese Invention Patent, Application No. CN119610116B, Granted.
* Chengxing Wu, Shizhong Tan, Jixiang Yang, and Han Ding. Robotic milling path error prediction method, system, and storage medium. Chinese Invention Patent, Application No. CN119691701B, Granted.

Research Funding Experience
======
* National Key Research and Development Program of China, Rigid-Flexible Coupled Dynamic Modeling and High-Precision Identification of Industrial Robots, Grant No. 2023YFB4703800.
  * Role: Formulated a Lie-theory-based unified kinematics-dynamics modeling framework considering joint compliance; led the design of a two-DOF active vibration suppressor for robotic milling with decoupled control force and pose-dependent adaptive control gain.
* Basic Science Center Program of the National Natural Science Foundation of China, Robotic Intelligent Manufacturing, Grant No. 52188102.
  * Role: Identified pose-dependent payload characteristics and engineered a neural-network-driven model for dynamic joint servo error prediction and proactive compensation.
* Joint Funds of the National Natural Science Foundation of China, Accuracy and Surface Quality Control in Robotic Compliant Machining of Large Complex Surfaces, Grant No. U24A20276.
  * Role: Defined tool-tip force-induced deformation error and developed a fast cutting-force calculation method for synergistic optimization of tool orientation and robotic redundancy angles.
* Young Scientists Fund of the National Natural Science Foundation of China, In-situ Detection and Compensation of Contour Error in Robotic Milling of Large Deep-Cavity Components, Grant No. 52305535.
  * Role: Proposed a multimodal data-fusion framework integrating robotic machining features with in-situ structured-light measurements for closed-loop contour-error compensation.

References
======
* Prof. Han Ding, Professor, School of Mechanical Science and Engineering, Huazhong University of Science and Technology. Email: [dinghan@hust.edu.cn](mailto:dinghan@hust.edu.cn). Relationship: Ph.D. co-supervisor.
* Prof. Jixiang Yang, Professor, School of Mechanical Science and Engineering, Huazhong University of Science and Technology. Email: [jixiangyang@hust.edu.cn](mailto:jixiangyang@hust.edu.cn). Relationship: Ph.D. supervisor.
