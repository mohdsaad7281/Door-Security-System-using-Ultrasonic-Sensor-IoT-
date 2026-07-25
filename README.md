# Door-Security-System-using-Ultrasonic-Sensor-IoT

An IoT-based door lock security system built by adapting a radar-style rotating ultrasonic sensor for real-time human presence detection, authorization checks, and remote alerts.

## Objective

Detect a person in front of a door using an ultrasonic sensor and secure the entry point accordingly.

This project modifies an existing radar-based detection system into a comprehensive **IoT Door Lock Security System**, intended for use in homes, offices, and restricted areas. It combines:

- **Radar Principle** — a rotating ultrasonic sensor scans the area near the door to detect human presence.
- **Authorization & Alerts** — verifies authorization, controls a buzzer, and gives visual feedback via OLED display and LEDs.
- **IoT Integration** — enables remote monitoring and control for smart, reliable security.

## 🎯 Project Objectives

| Objective | Description |
|---|---|
| **Convert Radar System** | Transform a radar detection system into a full door lock security system |
| **Detect Unauthorized Access** | Identify and prevent unauthorized entry near the door |
| **Visual & Audible Alerts** | Provide clear indications of security status through lights and sound |
| **Enable Remote Monitoring** | Use IoT technology for off-site surveillance and control |

## 🧩 System Architecture

| Component | Role |
|---|---|
| **Microcontroller (Arduino Uno)** | Central brain — coordinates all components for seamless operation |
| **Distance Sensor (Ultrasonic)** | Provides proximity readings to detect intrusions |
| **OLED Display** | Shows status, alerts, and sensor data in real time |
| **Actuators (LEDs, Buzzer, Servo)** | Signal alarms and control mechanisms |
| **IoT Module** | Enables remote monitoring and cloud notifications |

## 🛠️ Hardware Components

- Microcontroller — controls sensors, display, and motor
- Ultrasonic / IR Sensor — detects object distance and motion
- Servo Motor (SG90) — rotates the sensor for radar-like scanning
- OLED Display — shows real-time status and distance
- LEDs & Buzzer — provide visual and audio alert indications
- Power Supply — powers the entire security system

## 💻 Software Requirements

- Arduino IDE 
- Embedded C (vibe coding)
- IoT Platform (Wi-Fi based)
- OLED Display Libraries
- Servo Motor Library

## ⚙️ Working Principle

1. **Scan Area** — the rotating ultrasonic sensor continuously scans the area near the door.
2. **Detect Person** — presence is detected once an object/person enters range.
3. **Measure Distance** — the sensor measures proximity to confirm intrusion.
4. **Check Authorization** — the system verifies whether access is authorized.
5. **Activate Response** — triggers OLED/LED/buzzer alerts and (optionally) cloud notifications for unauthorized access.

Mohd Saad
