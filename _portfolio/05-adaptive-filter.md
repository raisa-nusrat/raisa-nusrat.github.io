---
title: "Noise Cancellation Using Adaptive Filters"
excerpt: "Comparison of LMS and RLS adaptive filters for removing noise from audio signals.<br/><img src='/images/filter-fft.jpg' width='300'>"
collection: portfolio
---

**Course:** EEE 312 Digital Signal Processing I Laboratory, BUET (team project)  
**Tools:** MATLAB

## Overview

Adaptive filters adjust their coefficients as the input changes, which makes them suited to removing noise whose properties are unknown or shifting. This project implemented LMS and RLS adaptive noise cancellers and compared them.

## Method

- Corrupted an audio signal with noise and used a reference noise input to cancel it.
- Implemented both LMS and RLS algorithms and varied the filter length.
- Compared the two by signal-to-noise ratio, mean squared error, and convergence speed.

## Outputs

![Frequency spectra before and after filtering](/images/filter-fft.jpg)

![Learning curve (mean squared error vs. iteration)](/images/filter-learning.jpg)
