---
title: "Multi-Modal Parkinson's Disease Detection"
excerpt: "Parkinson's disease detection from voice, gait, and handwriting, combined through late fusion.<br/><img src='/images/pd-voice.jpg' width='300'>"
collection: portfolio
---

**Course:** EEE 402 Artificial Intelligence and Machine Learning Laboratory, BUET (team project)  
**Tools:** Python, scikit-learn, deep learning

## Overview

Parkinson's disease affects speech, walking, and fine motor control. This project built a separate classifier for each of three signals and combined their outputs.

- **Speech:** acoustic features such as pitch, jitter, shimmer, and harmonics-to-noise ratio from sustained vowels.
- **Gait:** vertical ground-reaction force signals recorded while walking.
- **Handwriting:** spiral and wave drawings.
- **Fusion:** late fusion of the three classifiers' predictions.

## Outputs

![Voice feature distribution: Parkinson's vs. healthy controls](/images/pd-voice.jpg)

![Age distribution of participants](/images/pd-age.jpg)

This work is now being developed into a paper using the PADS smartwatch dataset.
