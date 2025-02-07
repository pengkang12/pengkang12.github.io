---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
---

{% include base_path %}

## Edge Stream Processing for Machine Learning Applications
  * Description
    - The proliferation of IoT devices and the exponential growth in data generation have rendered Machine Learning (ML) training and serving systems at the network edge of paramount importance. The deployment of ML models at the edge offers real-time decision-making, minimized latency, enhanced data privacy, and localized intelligence. However, the limited computational power, memory, and constrained energy budgets on edge devices hinder the deployment of sophisticated ML models, particularly large language models.
    - This research focus on developing system and middleware solutions for exploiting the ability of edge computing for ML model serving systems and distributed model training frameworks.

      ![image info](../images/IoT.png)

  * Specifications:
    * Hardware: Jetson Orin Series / Chameleon cloud
    * Operating System: Ubuntu
    * Software Stack: Microk8s/Kubernetes, Container, StreamCV, Apache Storm, OpenCV, Pytorch
    * Skills: Bash, Java, C++, Python, Machine Learning
  * This project includes two parts:
    * Explore the performance issues form application side
    * Explore the infrastructure performance by optimizing software and hardware
 


## Operating System Progmatics with Real Hardware
  * Description
    - This project is designed to provide students with hands-on, practical experience in applying the operating system principles learned in CSC 139, ensuring they develop a solid and comprehensive understanding of the design and implementation challenges involved in modern operating system development. I am currently updating these iterative projects to align with the latest hardware advancements. The project will cover key areas such as the project environment, hardware drivers, interrupts, CPU scheduling, memory management, and file systems.

  	![image info](../images/159-CurrentProject-new.png){width=50%}

  * [Project Slides](https://drive.google.com/file/d/1u6thlczTnHqV7ajLgfDGRxd-Jdrdz8lb/view?usp=sharing)
  * Hardware architecture: x86 (QEMU) /Arm64 (Raspberry Pi)
  * Skills: C, Shell, Linux, GNU Compiler, xv6
### Updated Progress 
  * Nov: I am currently working on Disk and a file system for Project Phase 6B.
  * Nov: I have built a demo file system into Project Phase 6A.
  * Oct: I have built a virtual memory management and user mode into Project Phase 3.5.

