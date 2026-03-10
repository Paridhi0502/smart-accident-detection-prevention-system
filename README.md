# Smart Accident Detection and Prevention System

## Overview
This project presents a smart vehicle safety system designed to detect accidents and prevent collisions using embedded systems and IoT technologies.

The system integrates Arduino UNO and ESP32 with multiple sensors to monitor vehicle motion and detect abnormal events.

## Features
- Obstacle detection using ultrasonic sensors
- Automatic braking mechanism
- Accident detection using MPU6050, and vibration sensors
- Emergency alert system with GPS location
- Telegram Bot notification system

## Hardware Components
- Arduino UNO
- ESP32
- Ultrasonic Sensor
- MPU6050
- Vibration Sensor
- GPS Module
- Power Supply
- Vehicle Prototype

## Software Used
- Arduino IDE
- Telegram Bot API

## Working Principle
The ultrasonic sensor continuously scans the surroundings for obstacles. If an object is detected within a critical distance, the system triggers automatic braking to avoid a collision.

If a sudden impact or abnormal movement is detected using the MPU6050, or vibration sensor, the system classifies it as an accident event.

Once detected, the ESP32 retrieves the GPS coordinates and sends an emergency alert via Telegram Bot. 

## Applications
- Smart Vehicle Safety Systems
- Accident Monitoring
- Emergency Response Systems
- IoT-based Transportation Safety

## Demo Video
https://youtu.be/s8-SW3dtShc

## Project Report
See the detailed report in the /report folder.

## Note:
The project source code will be uploaded soon.
Currently, the repository contains the project documentation, system architecture, and demonstration of the working prototype.
