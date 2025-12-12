# RobotNexus-IITMicromazeRobot-2025
Autonomous maze-solving robot built using ESP32, VL53L0X ToF sensors, N20 motors with encoders, and TB6612FNG drivers for IIT Micromaze Competition-2025.


🤖 RobotNexus – Autonomous ESP32 Micromaze IITMicromazeRobot-2025

This repository contains the full hardware and software implementation of RobotNexus, our autonomous maze-solving robot designed for the IIT Micromaze Competition.

Built using ESP32, VL53L0X ToF sensors, N20 motors with encoders, and a TB6612FNG motor driver, the robot navigates mazes using PID navigation, sensor fusion, and real-time decision-making.

⚙️ Robot Architecture
Core Components

MCU: ESP32 DevKit V1

Sensors: 3× VL53L0X ToF distance sensors

Motors: N20 geared motors with encoders

Motor Driver: TB6612FNG dual driver

Battery: 7.4V Li-ion

Power System: Buck converter for stable 5V output

🧭 Control & Navigation
Real-Time Processing

Multithreaded ESP32 loops

Non-blocking sensor polling

Fixed-rate update cycles

PID Navigation

Custom-tuned PID controller for fine tracking

Smooth cornering

Wall following with precision

Sensor Fusion

Front + left + right ToF readings

Junction classification

Obstacle avoidance

🧠 Software Architecture

Modular C++ codebase

State machine navigation

Path memory logging

Encoder-based motion feedback

Simplified debugging via layered code design

🔋 Power System

7.4V Li-ion battery

Single buck converter

Motor noise isolation

Stable sensor voltage for clean readings

👥 Team RobotNexus

Pasindu(Captain) – Embedded Programming, System Architecture & Optimization

Niven*(Vice Captain) –  Power Systems

Tharindu – Sensor Calibration

Chamath – Algorithms & Navigation

Mihan – Mechanical Design 


Proud of the engineering, innovation, and teamwork that brought RobotNexus to life. 🚀

📁 Repository Structure
/code.ino      → C++ source code (ESP32)
/photosmazerobot   → Wiring diagrams, PCB Photos, videos, architecture diagrams
README.md

▶️ How to Run

Open the /code folder in Arduino IDE or PlatformIO

Install:

Adafruit VL53L0X

Wire.h

ESP32 motor PWM libraries

Flash code to ESP32

Place robot at maze start and power on

📸 Media

Photos & videos located inside /photosmazerobot.

🔗 Connect With Us

Team: RobotNexus
Competition: IIT Micromaze 2025

🏷️ Hashtags

#RobotNexus #ESP32 #MazeSolver #Micromaze #Robotics #EmbeddedSystems #AutonomousRobots #ToFSensors #N20Motors #TB6612 #Cplusplus #SensorFusion #IITCompetition #SriLanka #Engineering #Innovation #STEM #StudentProjec
