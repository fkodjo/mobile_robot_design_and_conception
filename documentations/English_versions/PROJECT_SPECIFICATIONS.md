# Project Specifications
## 1. Background
After completing my master’s degree in Computer Science and Systems at EPL-UL in September 2025, I began the second year of the master’s program in Complex Systems Engineering, specializing in Robotics and Autonomous Systems, at UTBM. On the one hand, moving from theory to practice, I gained extensive knowledge of mobile robotics and computer vision—including, among other topics, visual servoing, camera calibration, optical flow, homography, triangulation, scheduling, PID, Kalman filtering, path tracking, kinematics, odometry, localization, SLAM, image processing, object detection, and deep learning. On the other hand, I also gained expertise in electronic circuit board design (PCBs using KiCad, from design to fabrication), electromagnetic compatibility, and embedded systems with STM32 board programming (CAN and LIN communication, UART, I2C, FreeRTOS, memory and energy optimization, and battery sizing).

If I’ve learned one thing throughout my career (primarily in computer systems and networks), it’s that the virtual world, as advanced as it may be, is vastly different from the physical world (what works in the virtual world doesn’t always work in the physical world). I noticed this again during my studies in robotics: the portability of programs from simulation to hardware, from ROS, RviZ, and Gazebo GYM to the Turtlebot3.
Based on these observations, I decided to buy a Turtlebot3 Burger (I didn’t yet have any knowledge of the BCP or embedded systems). By the end of spring 2026, after acquiring all this knowledge, I asked myself: “Why buy a robot when I could instead put all the skills I’ve acquired over the past year into practice by building one from scratch myself?”

It was with this in mind that I decided to build a CAR-type mobile robot myself; hence this project.

## 2. Objectives
## 2.1. General Objective
The general objective of this project is to build a mobile robot for experimental testing in mobile and/or industrial robotics.

## 2.2. Specific Objectives
To achieve the general objective, we will go through several stages, from which the following specific objectives are derived: 
 - Literature review
 - Sizing, schematics, and design of the PCB
 - Compliance testing of the PCB
 - Programming the STM32 microcontroller (communications)
 - Installation of the onboard computer
 - Design and 3D printing of the robot chassis
 - Final assembly
 - Testing (movement, SLAM, LIDAR, camera)

## 3. Technical Specifications
## 3.1. Hardware Specifications
 - Electronic components
 - 11.8V Li-Po battery
 - STM32 Nucleo-144 board (STM32H753ZI)
 - Raspberry Pi 4 Model B 8 GB
 - Lidar (RPLIDAR C1)
 - Logitech Brio 100 Full HD Webcam
 - 3D printer
 - Electronics breadboard
 - Multimeter
 - Oscilloscope

## 3.2. Software Specifications and Environment
 - STM32CubeIDE
 - FreeRTOS
 - Ubuntu
 - KiCad
 - FreeCAD
 - 

## 4 Expected Results
By the end of this project, we will have a prototype robot capable of:
 - moving according to mathematical models in robotics
 - integrating a camera, a LiDAR, and a 4- or 6-axis robotic arm into a ROS environment
 - 
## 5. Skills
By the end of this project, we will have acquired skills in:
 - Electronic circuit design
 - Designing circuit diagrams with KiCad
 - Designing printed circuit boards (soldering components)
 - Programming STM32 microcontrollers and communicating via CAN, UART, and I2C protocols
 - Installing and programming a Raspberry Pi
 - Configuring the ROS environment
 - 3D modeling and printing (FreeCAD)