---
title: "HIVE-R: Bio-Inspired Rescue Drone for GPS-Denied Environments"
show_date: false
excerpt: "Honeybee-inspired autonomous drone that finds people in disaster zones without GPS, using visual odometry and YOLOv8 detection.<br/><img src='/images/hiver-detection.jpg' width='300'>"
collection: portfolio
---

**Course:** Robotics and Automation, BUET (team project) — paper in preparation  
**Tools:** Pixhawk, Raspberry Pi 4, MPU6050 IMU, Python, YOLOv8-Nano, radio telemetry

## Overview

Floods, earthquakes, and building collapses often leave GPS unavailable, which stops conventional search-and-rescue drones. HIVE-R borrows the structure of a honeybee colony: several worker drones cover a search area and report victim locations to a central ground station.

## System

- **Navigation:** camera-IMU visual odometry (SLAM) gives each drone its position without GPS.
- **Detection:** YOLOv8-Nano trained on a human-detection dataset, with fuzzy augmentation for blur, smoke, and low light.
- **Reporting:** victim coordinates are sent to the ground control station over radio telemetry.

![System workflow](/images/hiver-flowchart.jpg)

## Outputs

The drone detected people mid-flight with high confidence and sent their coordinates back to the ground station reliably.

![Mid-flight human detection](/images/hiver-detection.jpg)
