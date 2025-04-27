---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
toc: true
toc_sticky: true
toc_label: "Sections"
css:
  - /assets/css/custom.css
---

<div class="small-text">
I have highlighted below a few of the projects that I have worked on during my undergraduate and graduate studies. There are both academic and industrial projects, and I have included a brief description of my role in each project. The progression of these projects indicates the evolution of my interests and skills from a heavy mechanical design focus to a more mechatronic and control systems focus. 
</div>

## FalconE Project (2019-2022)

<div style="display: flex; gap: 1rem; margin-bottom: 2rem;">
  <img src="/assets/images/FalconE_rearEnd.jpg" alt="FalconE Project" style="width: 50%;">
  <img src="/assets/images/FalconRear_endPic.jpg" alt="FalconE Front" style="width: 50%;">
</div>

![Suspension tasks](/assets/images/suspensionWorks.jpg){: width="100%" style="margin-bottom: 2rem;"}


<div id="project-description" markdown="1">
Sri Lanka's first and only active electric FSAE project, which targets FSAE competitions in Asia and Europe. The project is governed by the Department of Mechanical Engineering, University of Moratuwa. Even though the cohort of 2020-2022 was plagued by the COVID-19 pandemic, we managed to complete the design for the second generation of the car, which was essential in successfully competing in the Formula Bharat 2022 (virtual) competition and the [Formula Bharat 2024](https://www.formulabharat.com/archive/).

My role as the **Chief Technical Officer (CTO)** of the project was to lead the design and development of the car, prepare documentation and specifically to oversee the full vehicle assembly and testing. I was also responsible for the design and development of the suspension and steering systems, which included the following tasks:

- Complete mechanical design of Chassis, Suspension and Steering systems. Analysis of the suspension kinematics to design the optimum suspension geometry that complements the optimum tire traction profile in potential motion scenarios.
- Calculation of load cases under multiple dynamic situations to arrive at forces related to suspension and steering systems to choose and justify the Suspension spring and damper combination.
- Involved in CFD thermal analysis for performance evaluation of cooling ducts.

The mechanical design work was done using SolidWorks and the structural FEM analysis was done using **ANSYS**. Other supplementary tasks such as kinematic analysis, suspension geometry optimization and load case calculations were done using **MATLAB** and **OptimumKinematics**.
</div>

## ThermalR Industries Electric Motorbike (2021)

<div style="text-align: center;">
  <img src="/assets/images/ThermalR_Ebike.png" alt="ThermalR Bike" style="width: 50%;">
</div>

<div id="project-description" markdown="1">
This image showcases the prototype of the ThermalR Industries Electric Motorbike, which was a significant milestone in Sri Lanka's journey towards electric vehicle manufacturing.

This project, which was a part of the mandatory internship program at the University of Moratuwa, was one of the initial steps towards manufacturing electric vehicles in Sri Lanka. My role in the project involved the design and manufacturing process of the chassis and suspension systems of the e-bike prototype. This groundwork was essential in the development of Sri Lanka’s first electric bike, [Peregrine](https://thermalr.com/electric-bike/) which was launched in 2022.
</div>

## Battery pack design for Electric Vehicles - VEGA Innovations (2022)

![E-Bike](/assets/images/vegaBatteryPack.jpg){: width="100%" style="margin-bottom: 2rem;"}

<div id="project-description" markdown="1">
In this brief employment stint at VEGA Innovations, My role included design and development of battery packs for combustion to EV conversions. Additionally, I was also involved in developing tools to calculate the energy consumption of electric vehicles relative to a given driving cycle. A design I developed for a company driven public assignment can be found [here](https://cad.onshape.com/documents/90e1694263529daeff9b79a5/w/af57081e9c6b6cbfe200de79/e/7a75224d8f3db6c6459aced6).
</div>

## Projects related to MOOC Specializations (2023)

### Self-Driving Car Specialization - University of Toronto

![My Project Animation](/assets/videos/FinalProjectMotionPlanning.gif){: width="100%" style="border-radius: 8px; margin-bottom: 1rem;"}

<div id="project-description" markdown="1">
The year after completing my bachelor's degree and while working as a TA at the University of Moratuwa, I completed the Self-Driving Car Specialization offered by the University of Toronto. This specialization provided me with a comprehensive understanding of the key concepts and technologies involved in self-driving cars, including vehicle control systems visual perception, sensor fusion, localization and motion planning. 

The simulation platform CARLA was used to implement the project milestones. The projects included:
- Control system implementation for a path following.
- Use of Error-state Kalman filter for localization.
- Visual Odometry using OpenCV.
- Motion planning (mission, behavior and trajectory planning).
</div>

<!--
### Applied Control Systems and Arial Robotics Experience 

The increasing relevance of control systems within the field of autonomous vehicles led me to persue more knowledge in this area. With the completion of ![Applied Control Systems](https://www.udemy.com/course/applied-systems-control-for-engineers-modelling-pid-mpc/) and Arial Robotics Specialization offered by the University of Pennsylvania on 
-->

<!-- ============================================================ -->
## Mechatronic Design and Embedded Systems
<!-- ============================================================ -->

### Hecate Project (2024)

<div style="display: flex; justify-content: center; gap: 1rem; max-width: 900px; margin: 0 auto 2rem;">
  <img src="/assets/videos/hecateTurning.gif" alt="FalconE Project" style="width: 45%;">
  <a href="/assets/images/hacateFinal4.png" target="_blank" style="width: 100%;">
    <img src="/assets/images/hacateFinal4.png" alt="FalconE Project" style="width: 100%;">
  </a>
</div>

<div id="project-description" markdown="1">
This project was initiated with an intension to develop a low-cost mobile robot platforms for research and education. From a design perspective, the focus was to make the robot modular and easy to assemble, while also allowing easy access for augmentation and modification. The robot footprint was designed to be as small as possible (13 cm), while still allowing for a large enough battery pack to be installed. The whole structure was designed to be 3D printed. 

The embedded hardware and software implementation included the following tasks:
- Creating a custom wrapper for **DynamixelSDK**, enabling low-level motor control for a 2-wheeled robot operating in dynamic environments.
- Using Lightweight Communications and Marshalling ([LCM](https://github.com/lcm-proj/lcm)) protocols for fast, efficient real-time communication between the control system and robot.
</div>

### Eris (Enhanced Rotational Instable System)

<div style="text-align: center;">
  <img src="/assets/images/experiment_setup.png" alt="ThermalR Bike" style="width: 50%;">
</div>

<div id="project-description" markdown="1">

The updated version of the conventional **Ball-on-Wheel** system, which is a nonlinear control experiment. The project was to be used for teaching and research purposes. The system is fully mobile and houses an onboard controller while also allowing for external control. Similar to the Hecate project, the mechanical design as well as the embedded hardware and software implementation was done by me.

- Designed a robust embedded control architecture for real-time sensing, actuation, and communication.
- Implemented sensor fusion strategies using redundant Time-of-Flight (ToF) measurements.
- Developed precise motor control schemes tailored for nonlinear dynamic stabilization.
- Integrated high-speed communication between the embedded controller and a Simulink-based control environment.

**Hardware:**
- NEMA17-06 with TMC2208 stepper driver
- Dual VL53L0X modules for redundant position detection
- ESP32-S3 Microcontroller
</div>

