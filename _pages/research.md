---
permalink: /research/
title: "Research"
author_profile: true
---

## Publications

### Journal Articles

1. **R. Nusrat**, M. R. Rahman, I. J. Riya, and M. Faisal, "Age-Robust Stroke Detection and Paretic-Side Identification Using Nasolabial Fold Asymmetry and Clinical Data," *IEEE Journal of Biomedical and Health Informatics*, under review, 2026.
2. **R. Nusrat**, M. S. Raihan, S. M. R. Rahman, H. Saha, and S. S. Ahbab, "A Low-Cost Integrated Motorcycle Theft Detection and Monitoring System Using Arduino, ESP32-CAM, and GSM/GPS Technologies," *Journal of the Electrical and Electronic Engineering Division, Institution of Engineers, Bangladesh (IEB)*, accepted, 2026.

### Conference Papers

1. **R. Nusrat**, "When Scale Flips the Answer: Corridor-Level Deep Reinforcement Learning for Traffic Signal Control on a Simulated Dhaka Arterial," *AABEA 2026 Biennial Convention*; abstract accepted for proceedings, full paper under review.
2. **R. Nusrat**, "Rare-Attack Blindness in Federated Intrusion Detection for the Internet of Medical Things," *14th International Conference on Electrical and Computer Engineering (ICECE 2026)*, Dhaka, under review.

### Manuscripts in Preparation

1. **R. Nusrat** et al., "Differentiating stroke from ALS using facial-motion asymmetry on the Toronto NeuroFace dataset."
2. **R. Nusrat** et al., "Parkinson's disease detection using the PADS smartwatch dataset."
3. **R. Nusrat**, A. Hamim, M. Fahim, M. J. Hasan, and A. Hasan, "HIVE-R: Bio-inspired and visual odometry based drone for rescue operations in GPS-denied environments."

## Undergraduate Thesis

**A Multimodal Deep Learning Framework for Stroke Detection from Facial Asymmetry and Clinical Data with Explainable AI and External Validation**  
Supervisor: Dr. Mohammad Faisal, Professor, Department of EEE, BUET  
Completed June 2026

Stroke often causes visible facial asymmetry, but recognizing it quickly depends on trained clinical staff. In this two-member thesis, we built a dataset of 117 patients (71 stroke, 46 non-stroke) from hospital records in Dhaka, combining facial images with routine blood test results.

We trained a Siamese network that compares the left and right sides of the face around the nasolabial folds and mouth, alongside a clinical model using laboratory features, and fused the two. The image model reached an AUC of 0.983, and on 15 held-out external patients the fused model achieved 80% accuracy and 88.9% sensitivity.

After the thesis, I expanded the dataset to 181 inpatients for the journal version, now under review at *IEEE JBHI*. In 53 age-matched pairs, seven nasolabial fold asymmetry features reached an AUC of 0.748, while a 28-variable clinical model fell to 0.596, and the fold asymmetry identified the paretic side with an AUC of 0.908.

## Ongoing Clinical Study

**Multimodal Stroke Detection Using Facial Imaging and Blood Biomarker Analysis**  
Approved by the BUET Ethical Review Committee (Ref. BUET/ERC/2026/01). Supported by the Basic Research Grant, RISE, BUET.

## Independent Research

**Deep Reinforcement Learning for Traffic Signal Control**  
Built a five-junction Dhaka corridor in SUMO and trained a shared-policy deep Q-network. Under saturated traffic, it cut arterial delay by 60% and cross-street delay by 41% compared with fixed-time control.
