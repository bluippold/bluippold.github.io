---
layout: post
title: Dual-zone TCU
description: "A pneumatically actuated system designed for thermal contact with LGA packages, featuring a TEC-integrated head for 0°C–120°C operation. Includes a purge chamber to prevent condensation and two thermal zones: a passively cooled CPU zone and an actively controlled I/O zone with PID-regulated TECs and RTD feedback."
card-image: /_projects/TCU1/TCU1ThermalHead.JPG
skills: 
- Mechanical Design
- Thermal Design (FEA & CFD)
- Pneumatics and Actuation
- Strength of Materials
- Environmental Sealing
- Tolerance Stackup
---

<img src="/_projects/TCU1/TCU1.JPG" alt="Dual-zone TCU" class="centered-image" />

### Table of Contents
- [Overview](#overview)
- [Thermal Head Design](#thermal-head-design)
- [Pneumatic Actuation](#pneumatic-actuation)
- [Dual-Zone Architecture](#dual-zone-architecture)
- [Purge System](#purge-system)
- [Control and Sensor Integration](#control-and-sensor-integration)
- [Prototyping and Assembly](#prototyping-and-assembly)
- [Challenges and Design Iterations](#challenges-and-design-iterations)

---

### Overview

This dual-zone temperature control unit (TCU) is designed for thermal contact with LGA semiconductor packages during validation testing. The system features a pneumatically actuated thermal head with TEC integration, supporting precise thermal control from 0°C to 120°C across two independently controlled zones: the central CPU area and the surrounding I/O region.

---

### Thermal Head Design

The thermal head is precision-machined to match the device under test. It integrates thermoelectric coolers (TECs) on the outer I/O zone, while a passive copper plate and chilled water loop manage the inner CPU zone. A spring-loaded contact mechanism ensures uniform pressure and thermal contact across both areas.

---

### Pneumatic Actuation

A pneumatic cylinder applies vertical force to bring the thermal head into contact with the device. The actuation system includes adapter plates for alignment and compatibility with various customer PCB stackups. This approach ensures consistent and repeatable engagement across different hardware configurations.

---

### Dual-Zone Architecture

The TCU separates thermal control into two zones:  
- **CPU Zone:** passively cooled via a water chiller loop.  
- **I/O Zone:** actively controlled using four TECs regulated by a PID controller.  

This design allows different components on the same LGA package to be held at different temperatures during testing.

---

### Purge System

A transparent polycarbonate housing forms a sealed purge chamber around the thermal head. Dry air is introduced to prevent condensation during low-temperature operation, protecting sensitive electronics and maintaining consistent thermal performance.

---

### Control and Sensor Integration

The I/O zone is regulated using an external PID controller, with RTD sensors placed near the contact surface to ensure accurate real-time feedback. All sensors and TECs are routed through custom wire harnesses for ease of integration and maintenance.

---

### Prototyping and Assembly

The full system was prototyped using CNC-machined components, 3D-printed housings, and machined polycarbonate parts. The design was iteratively refined to balance thermal performance, manufacturability, and system integration with the test socket and PCB assembly.

---

### Challenges and Design Iterations

- Preventing cross-talk between thermal zones  
- Ensuring condensation-free operation at 0°C  
- Managing wire routing in a compact, actuated assembly  
- Designing modular components compatible with various customer hardware
  
---

📄 [Download PDF Summary](./TCU1-summary.pdf)
