# TrackAlert Vision

An Autonomous Indoor Patrol and Safety Monitoring Robot

## About the Project

TrackAlert Vision is a robotics project developed for the CSE461: Introduction to Robotics course at BRAC University.

The robot is designed to patrol indoor environments by following a predefined line, avoiding obstacles, detecting motion, and monitoring environmental hazards. It can send alerts and captured images to help an operator monitor the environment remotely.

## Features

- Line following using IR sensors
- Obstacle detection and avoidance using an ultrasonic sensor
- Human motion detection using a PIR sensor
- Smoke and gas monitoring using an MQ-2 sensor
- Flame detection
- Tilt detection using an MPU6050 sensor
- Camera-based monitoring using an ESP32-CAM-family board
- Image alerts through a Telegram bot
- Buzzer and LCD alerts
- Wireless monitoring and safety notifications

## Hardware Components

- ESP32-CAM-family camera board
- IR line-following sensors
- Ultrasonic sensor
- PIR motion sensor
- MQ-2 gas/smoke sensor
- Flame sensor
- MPU6050 IMU
- DC gear motors and wheels
- L298N motor driver
- Robot chassis
- Battery power supply
- Buzzer and LCD
- Jumper wires and other circuit components

## Software and Technologies

- Arduino IDE
- Embedded C/C++
- ESP32
- Wi-Fi communication
- Telegram bot notifications
- Web-based monitoring

## How It Works

1. The robot follows a predefined track using IR sensors.
2. The ultrasonic sensor checks for obstacles.
3. The robot avoids obstacles and attempts to return to its track.
4. The PIR sensor detects motion.
5. The camera captures images for monitoring and alerts.
6. The environmental sensors monitor potential hazards.
7. Tilt detection and alert logic help respond to unsafe conditions.
8. Notifications are sent to the operator when configured events are detected.

## Testing and Results

The project report documents tests for line following, obstacle avoidance, route recovery, motion detection, flame detection, gas/smoke detection, tilt detection, image delivery, and alert handling.

Results depend on sensor calibration and the test environment.

## Project Gallery

Project photos will be added here.

## Project Demonstration

- 🎥 **Watch the Demo on YouTube:** [TrackAlert Vision System Demonstration](https://www.youtube.com/watch?v=hXbFTyaiIrY)
- 📄 **Detailed Demo Notes & Timestamps:** [media/demo/README.md](media/demo/README.md)

## Documentation

The project report and technical diagrams will be added to this repository.

## Limitations

- Navigation depends on a predefined physical line.
- Sensor readings can require calibration.
- Ultrasonic sensing provides limited environmental detail.
- Camera processing capabilities are limited.
- Motion detection may produce false alerts.

## Future Improvements

- Multiple patrol routes
- Scheduled patrols
- Improved power management
- Cloud-based monitoring
- More advanced camera processing
- Navigation without a physical line

## Team Members

| Name | Student ID |
|---|---|
| Rezowana Mehjabin Lorel | 20201089 |
| Ahsan Habib | 22201027 |
| Sharan Mistry | 22201779 |
| Atahar Shihab | 22301336 |
| Maliha Binte Shamim | 23101466 |

## Course

CSE461: Introduction to Robotics  
Department of Computer Science and Engineering  
BRAC University
