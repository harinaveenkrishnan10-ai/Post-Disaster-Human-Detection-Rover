# 🚑 Post-Disaster Human Detection Rover using LoRa Mesh Network

A swarm-based cyber-physical rescue rover designed for post-disaster search and rescue operations. The system combines autonomous navigation, Edge Impulse AI vision, GPS localization, and long-range LoRa mesh communication to detect human survivors and relay their location to a remote rescue station even when conventional communication infrastructure is unavailable.

---

# Project Overview

Natural disasters often damage cellular and internet infrastructure, making communication difficult for rescue teams.

This project develops a dual-rover system capable of

- Autonomous obstacle avoidance
- Human detection using Edge Impulse AI
- GPS location tracking
- Long-range LoRa communication
- Mesh-based packet forwarding
- Remote monitoring through a dashboard

Each rover works independently while also acting as a communication node for the swarm.

---

# Features

- Autonomous obstacle avoidance
- Dual-rover swarm architecture
- LoRa RF Mesh networking (433 MHz)
- Edge Impulse AI human detection
- ESP32-CAM vision processing
- GPS-based victim localization
- RSSI monitoring
- Packet forwarding between rovers
- Multi-controller architecture
- Rescue station dashboard

---

# Hardware

- Raspberry Pi Pico W
- ESP32 AI Thinker Camera
- ESP8266 NodeMCU
- SX1278 LoRa Module
- Neo-6M GPS
- MPU6050 IMU
- HC-SR04 Ultrasonic Sensors
- L298N Motor Driver
- DC Geared Motors
- 18650 Li-ion Battery Pack

---

# Software

- MicroPython
- Arduino IDE
- Edge Impulse
- LoRa Library
- TinyGPS++
- Raspberry Pi Pico SDK

---

# System Architecture

(Add block diagram here)

---

# Working Principle

1. Rover autonomously explores the disaster area.
2. Ultrasonic sensors avoid obstacles.
3. ESP32-CAM performs Edge Impulse object detection.
4. Human detection generates an alert.
5. Pico W formats the packet.
6. ESP8266 appends GPS information.
7. LoRa transmits the packet.
8. Nearby rover forwards the packet if required.
9. Rescue station receives and displays victim location.

---

# Communication Flow

ESP32-CAM
↓

Pico W

↓

ESP8266

↓

LoRa Mesh

↓

Base Station

↓

Dashboard

---

# Results

- Successful autonomous navigation
- Human detection using Edge Impulse
- GPS location transmission
- Multi-hop LoRa communication
- Reliable packet forwarding
- RSSI monitoring

---

# Images

## System Architecture

(Add architecture image)

## Autonomous Navigation Flowchart

(Add flowchart)

## Human Detection

(Add detection screenshot)

## LoRa Alert

(Add transmission screenshot)

---

# Applications

- Search and Rescue
- Earthquake Response
- Landslide Monitoring
- Flood Rescue
- Forest Search Operations
- Defence Surveillance

---

# Future Improvements

- Multi-hop routing optimization
- SLAM-based navigation
- Thermal camera integration
- Drone-rover collaboration
- Cloud dashboard
- AI victim classification

---

# Author

Harikrishnan N.

B.Tech Electrical and Electronics Engineering

Amrita Vishwa Vidyapeetham

---

# License

MIT License
