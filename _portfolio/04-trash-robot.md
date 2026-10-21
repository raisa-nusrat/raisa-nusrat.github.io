---
title: "Autonomous Trash-Collecting Line-Following Robot"
excerpt: "PID-controlled line-following robot that detects objects on its path and collects them.<br/><img src='/images/robot-detection.jpg' width='300'>"
collection: portfolio
---

**Course:** EEE 318 Control System I Laboratory, BUET (team project)  
**Tools:** Arduino, IR sensor array, L298N motor driver, custom PCB, PID control

## Overview

A robot that follows a track, finds waste in its path, and collects it automatically.

## Design

- **Line following:** an IR sensor array estimates the line position, and a PID controller sets the motor speeds.
- **Collection:** an object-detection sensor triggers an arm that picks up the item.
- **Hardware:** a custom PCB, designed and fabricated for the robot.

![PCB design](/images/robot-pcb.jpg)

## Outputs

After PID tuning, the robot followed curved tracks smoothly and collected objects along the way.

![Object detection](/images/robot-detection.jpg)

![Following the track](/images/robot-track.jpg)
