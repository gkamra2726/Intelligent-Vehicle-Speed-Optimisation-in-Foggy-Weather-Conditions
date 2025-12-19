# Intelligent Vehicle Speed Optimization in Foggy Weather Conditions

## Overview
This project presents an ESP32-based intelligent vehicle system designed to enhance road safety in foggy and low-visibility conditions. The system dynamically adjusts vehicle speed based on real-time visibility and obstacle detection using sensors, reducing the risk of accidents caused by poor human judgment in adverse weather.

## Problem Statement
Foggy weather significantly reduces visibility, making manual speed control unreliable and dangerous. Traditional driving relies heavily on driver perception, which can be inconsistent. This project aims to automate speed regulation using sensor data to ensure safer driving conditions.

## Objectives
- Automatically adjust vehicle speed based on fog density and obstacle distance  
- Detect visibility levels using sensors  
- Provide real-time alerts to the driver  
- Demonstrate the application of embedded systems and IoT concepts in transportation safety  

## Working Principle
- An **LDR sensor** measures light intensity to estimate fog density (low light → dense fog).  
- An **ultrasonic sensor (HC-SR04)** detects obstacles and measures distance ahead of the vehicle.  
- The **ESP32 microcontroller** processes sensor data and controls motor speed using PWM signals.  
- Alerts are generated using a **buzzer and LCD display** when visibility is low or obstacles are close.

## Components Used
- ESP32 WiFi Module  
- LDR (Light Dependent Resistor)  
- HC-SR04 Ultrasonic Sensor  
- L298N Motor Driver Module  
- DC Gear Motors  
- Robotic Car Chassis  
- 16x2 LCD Display  
- Buzzer  
- Fog/Smoke source (for simulation)  
- Jumper wires, battery, switch , laser module  

## Features
- Adaptive speed control based on real-time sensor input  
- Obstacle detection for collision avoidance  
- Audio and visual alerts for the driver  
- Modular and scalable embedded system design  

## Challenges Addressed
- Accurate calibration of LDR for fog simulation  
- Synchronization of multiple sensors  
- Real-time motor speed control using PWM  
- Hardware integration and embedded programming on ESP32  

## Applications
- Smart vehicles and driver-assistance systems  
- Road safety enhancement in fog-prone areas  
- Educational embedded systems and IoT projects  

## Repository Contents
- Source code for ESP32  
- Project documentation   
- Circuit design and component details  

## Future Improvements
- Integration with real weather data  
- GPS-based speed regulation  
- Machine learning for better visibility estimation  
- Vehicle-to-vehicle communication  
