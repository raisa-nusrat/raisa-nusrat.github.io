---
title: "Motorcycle Theft Detection and Monitoring System"
excerpt: "Low-cost security unit with PIN-locked ignition, live camera view, and GPS/SMS tracking. Accepted in the Journal of EED, IEB.<br/><img src='/images/moto-prototype.jpg' width='300'>"
collection: portfolio
---

**Course:** EEE group design project, BUET — journal paper accepted (Journal of EED, IEB)  
**Tools:** Arduino Uno, ESP32-CAM, SG90 servo, NEO-7M GPS, SIM800L GSM, HC-05 Bluetooth

## Overview

Most low-cost motorcycle security systems do only one or two of three jobs: tracking the vehicle, controlling the ignition, and recording the thief. This unit does all three using two inexpensive controllers.

## System

- **Ignition control:** the rider enters a PIN on a keypad to close the ignition relay; three wrong attempts lock the keypad.
- **Camera:** after a wrong PIN, an ESP32-CAM on a servo starts a live view over its own Wi-Fi while sweeping the scene.
- **Tracking:** GPS coordinates are texted to the owner every 60 seconds, with the ignition on or off.
- **Remote control:** the owner can block, unblock, or reset the system over Bluetooth.

![Hardware assembly](/images/moto-hardware.jpg)

## Outputs

Every subsystem met its requirements and all of them ran together without conflict. Parts cost 5390 BDT, or about 3800 BDT in bulk, with no subscription fee.

![Working prototype](/images/moto-prototype.jpg)
