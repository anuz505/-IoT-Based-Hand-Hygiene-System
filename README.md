# IoT-Based Hand Hygiene System

This repository contains the Tinkercad (BRD) file for an **IoT-Based Hand Hygiene System** designed to automate hand sanitizer dispensing and monitor sanitizer levels in real time. The project incorporates various hardware components such as ultrasonic sensors, a servo motor, an ESP8266 WiFi module, and an Arduino Uno microcontroller, with cloud-based monitoring via the ThingSpeak API.

## Project Overview

The IoT-Based Hand Hygiene System addresses the need for efficient, automated hygiene solutions in public spaces. It ensures continuous availability of hand sanitizer and reduces the need for manual maintenance checks by providing real-time alerts and usage analytics. This system is ideal for high-traffic environments such as hospitals, schools, malls, and offices.

### Key Features

- **Dual Ultrasonic Sensors**: One sensor detects hand presence to trigger dispensing, while the other monitors sanitizer levels.
- **Cloud-Based Monitoring**: Real-time data is sent to the cloud using the ESP8266 WiFi module and ThingSpeak API for remote monitoring.
- **Automated Alerts**: Sends notifications when sanitizer levels are low, ensuring timely refills.
- **Eco-Friendly Refill System**: Supports sustainable refillable containers to reduce plastic waste.
- **Scalability and Customization**: Adaptable for different environments, with adjustable settings for various use cases.

## Components

- **Arduino Uno**: Microcontroller used to process sensor data and control the system.
- **Ultrasonic Sensors (HC-SR04)**: Used for hand detection and monitoring sanitizer levels.
- **Servo Motor (SG90)**: Dispenses sanitizer when a hand is detected.
- **ESP8266 WiFi Module**: Enables wireless communication and sends data to the cloud.
- **LED Indicator**: Provides a visual alert when sanitizer is running low.
- **ThingSpeak API**: Cloud platform for remote monitoring and data analytics.

## How to Use

1. **Download the BRD File**: Download the Tinkercad BRD file from this repository.
2. **Open in Tinkercad**: Import the file into Tinkercad to view and simulate the circuit.
3. **Modify and Customize**: Feel free to customize the components and settings according to your requirements.
4. **Deploy on Hardware**: After testing the simulation, build the system using physical components and program it using the provided Arduino code.


## Acknowledgments

- **Tinkercad** for the easy-to-use simulation environment.
- **Arduino** for their extensive library ecosystem and user-friendly microcontroller.
- **ThingSpeak** for providing a robust cloud API for IoT projects.

---


