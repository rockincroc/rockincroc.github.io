---
title: "Practical Design and Orchestration of Frequency-Shifting RIS for NLoS mmWave Sensing"
collection: publications
permalink: /research/2025-RIS-sensing
excerpt: 'mmWave radar powers next-generation sensing in ISAC systems but struggles in non-line-of-sight environments. PRISM breaks through these limits, using RIS-based spatial modulation to turn angular cues into frequency shifts—boosting resolution without heavy computation or tight synchronization. The result: faster, more adaptable radar sensing that works where others fail.'
date: 2025-07-20
venue: 'ACM MobiHoc'
paperurl: 'https://rockincroc.github.io/files/MobiHoc2025_RIS_Sensing.pdf'
# citation: 'Aadesh Madnaik and Karthikeyan Sundaresan. 2025. Practical Design and Orchestration of Frequency-Shifting RIS for NLoS mmWave Sensing. In Proceedings of the Twenty-sixth International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing (MobiHoc 2025).'
---
<center><img src="/images/2025-rissensing-scenario.png" alt="Scenario" width="500"/></center>
<br>
mmWave radar sensing is essential for Integrated Sensing and Communication (ISAC) but is limited by the need for LoS in environments with obstacles. However, existing NLoS solutions, including those leveraging reconfigurable intelligent surfaces (RIS) are computationally demanding, unable to generalize to new surroundings or require tight synchronization/coordination that prevent practical deployments. We propose *PRISM*, a framework that brings the diversity of a RIS to monostatic radars to enhance target resolution in NLoS, all without requiring real-time coordination. PRISM uses spatial modulation at the RIS to encode targets’ angular information through frequency shifts by creating a time-variant channel for improved detection at the radar. Key contributions include a wideband spatial modulation framework, a genetic algorithm to efficiently solve for the RIS configuration to enable such angle-dependent frequency shifts, and a narrowband approximation method to reduce the computational overhead.

<center><img src="/images/2025-rissensing-principle.png" alt="RIS Principle" width="500"/></center>

[Download paper here](https://rockincroc.github.io/files/MobiHoc2025_RIS_Sensing.pdf)

<!-- Recommended citation: A. Madnaik, N. C. Matson and K. Sundaresan, "Scalable Network Tomography for Dynamic Spectrum Access," IEEE INFOCOM 2024 - IEEE Conference on Computer Communications, Vancouver, Canada, 2024 -->