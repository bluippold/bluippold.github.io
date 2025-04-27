---
layout: post
title: Custom TCU Controller
description: "A sheet metal enclosure housing the full control system for TCU operation. The assembly integrates switching power supplies, amplifiers, PID controllers, and custom wire harnesses, with an onboard Arduino microcontroller enabling remote connectivity and software integration for multi-zone thermal control."
main-image: /_projects/controller/Controller2.JPG
skills:
  - Sheet Metal Enclosure Design
  - Electrical Integration
  - Wire Harness Design
  - Power Distribution
  - Sensor & Control Integration
  - Prototyping & Assembly
---

# Custom TCU Controller

### Table of Contents
- [Project Purpose](#project-purpose)
- [Sheet Metal Enclosure Design](#sheet-metal-enclosure-design)
- [Power Distribution Architecture](#power-distribution-architecture)
- [Wire Harness and Cable Routing](#wire-harness-and-cable-routing)
- [Controller Electronics Integration](#controller-electronics-integration)
- [Remote Operation and Arduino Integration](#remote-operation-and-arduino-integration)
- [Assembly and Prototyping](#assembly-and-prototyping)
- [Challenges and Lessons Learned](#challenges-and-lessons-learned)

---

### Project Purpose

This controller was designed to operate multi-zone temperature control units (TCUs) for semiconductor device testing. It provides clean power distribution, thermal control, and remote operability in a compact, ruggedized enclosure suitable for benchtop use. Contains serial connectivity to water chillers as a safety shutoff in case TCU heat exchanger overheats (RTD sensor) and to PC for software program. 

---

### Sheet Metal Enclosure Design

The enclosure was modeled for efficient CNC sheet metal fabrication, with attention to airflow, cable passthroughs, and modular component mounting. Panels were designed for easy access during assembly and servicing, while maintaining a clean external appearance.

---

### Power Distribution Architecture

The internal layout supports two switching power supplies feeding multiple subsystems including TEC drivers, PID controllers, and auxiliary components such as RTD sensors. Heatsinks and active cooling fans were incorporated for thermal management of high-power components. Contains a 12V relay for powering PCB auxiliary components.

---

### Wire Harness and Cable Routing

Custom wire harnesses were designed and fabricated to interconnect all internal systems. Connectors were selected for reliability and serviceability, and cable routing was optimized to prevent interference, reduce noise, and enable clean separation of power and signal lines. All wires were secured with cable ties to designed mounting slots on machined frames.

<img src="/_projects/controller/PurpleBoard.jpg" 
     alt="Wire harness and cable routing in TCU Controller" 
     class="centered-image" 
     style="max-height: 500px; width: auto; transform: rotate(90deg);" />

---

### Controller Electronics Integration

The enclosure integrates dual PID controllers for independent zone regulation, with modular output wiring to drive TECs and sensors. Terminal blocks and distribution boards allow for flexible reconfiguration depending on system requirements.

---

### Remote Operation and Arduino Integration

An onboard Arduino microcontroller enables remote command and monitoring capabilities, interfacing with external software for automated control of temperature setpoints, system monitoring, and safety interlocks.

---

### Assembly and Prototyping

Prototyping involved CNC-machining, hand-wiring, and iterative fit checks to validate component placement and serviceability. Final assembly required integration of power electronics, control systems, and thermal management hardware.

---

### Challenges and Lessons Learned

- Managing heat buildup in a compact, enclosed system  
- Designing clean and serviceable wire routing within tight space constraints  
- Balancing modularity and system robustness for field use  
- Integrating custom control logic while maintaining electrical safety standards

