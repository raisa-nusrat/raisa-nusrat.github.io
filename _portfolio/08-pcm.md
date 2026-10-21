---
title: "PCM Line Code Generation"
excerpt: "Pulse code modulation system that samples, quantizes, and encodes an analog signal, built in hardware and simulation.<br/><img src='/images/pcm-block.jpg' width='300'>"
collection: portfolio
---

**Course:** EEE 310 Communication Systems I Laboratory, BUET (team project)  
**Tools:** Digital logic ICs, 555 timer, Proteus

## Overview

Pulse code modulation converts an analog signal into digital data. This project built the full chain in hardware.

- **Sampler:** samples a sine wave at fixed intervals.
- **Quantizer:** maps each sample to a discrete level using comparators.
- **Encoder:** converts each level to a binary code, shown on LEDs.

![PCM system](/images/pcm-block.jpg)

## Outputs

![Simulated sampling and encoding](/images/pcm-sim.jpg)
