# 📹 TrackAlert Vision — Project Demonstration

[![TrackAlert Vision YouTube Demo](https://img.youtube.com/vi/hXbFTyaiIrY/maxresdefault.jpg)](https://www.youtube.com/watch?v=hXbFTyaiIrY)

> 🔗 **Direct Video Link:** [Watch the Full Demonstration on YouTube (2m 45s)](https://www.youtube.com/watch?v=hXbFTyaiIrY)

---

## 📌 Demonstration Overview

This video demonstrates the end-to-end functionality of **TrackAlert Vision** (V1.5) — an autonomous household detection and protection robot developed for **CSE461: Introduction to Robotics** at **BRAC University**.

The robot patrols indoor environments along a predefined line, avoids obstacles, detects human motion, monitors environmental hazards (smoke, gas, and flame), and transmits alerts with captured images.

---

## ⏱️ Video Highlights & Features Demonstrated

| Timestamp | Demonstrated Feature | Subsystem / Sensors Involved |
| :--- | :--- | :--- |
| **0:00 - 0:45** | **Autonomous Line Following** | IR sensor array, dual DC gear motors, L298N motor driver |
| **0:45 - 1:20** | **Obstacle Detection & Avoidance** | Ultrasonic sensor (HC-SR04) |
| **1:20 - 1:55** | **Hazard Monitoring & Local Alerts** | MQ-2 gas/smoke sensor, Flame sensor, Buzzer & 16x2 LCD |
| **1:55 - 2:30** | **Motion Detection & Remote Alerts** | PIR motion sensor, ESP32-CAM Wi-Fi image transmission |
| **2:30 - 2:45** | **Patrol Wrap-up & Status Check** | System status telemetry & Telegram notifications |

---

## 🛠️ Key Hardware Tested in Demo

- **Processing & Control:** ESP32-CAM + Arduino board
- **Motor Control:** L298N dual H-bridge motor driver with DC gear motors
- **Sensing Suite:**
  - Infrared (IR) line-tracking sensors
  - Ultrasonic distance sensor (HC-SR04)
  - PIR human motion sensor
  - MQ-2 gas/smoke sensor
  - Optical flame sensor
  - MPU6050 6-DOF IMU (tilt/flip detection)
- **Alerting & Communication:**
  - 16x2 I2C LCD screen
  - Active piezo buzzer
  - Telegram Bot alerts with real-time photo capture over Wi-Fi

---

## 📂 Related Links

- 🏠 [Main Project README](../../README.md)
- 💻 [Source Code & Firmware](../../src/)
- 🔌 [Circuit & Hardware Documentation](../../hardware/)
- 📸 [Project Photos](../../media/photos/)
