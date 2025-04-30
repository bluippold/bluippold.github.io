---
layout: post
title: Heater Lid
description: "A semi-passive thermal lid that uses a Kapton heater mounted to an insulated heatsink to elevate and control temperature across the I/O zone of a semiconductor package. A central fan provides convective cooling over the CPU region for thermal partitioning."
card-image: /_projects/HeaterLid/HeaterLid.JPG
skills:
  - Thermal Architecture Design
  - Flexible Heating Systems (Kapton)
  - Passive and Forced Convection Cooling
  - RTD Integration and Temperature Sensing
  - Insulation and Heat Shielding
  - Semiconductor Validation Hardware
---

# Kapton-Heated Lid Assembly

<img src="/_projects/HeaterLid/HeaterLid.JPG" alt="Kapton-Heated Lid Assembly" class="centered-image" />

---

## Project Overview

This project involved the development of a thermally partitioned lid for benchtop semiconductor validation. The outer I/O zone is actively heated via a Kapton heater mounted to a thermally isolated heatsink, while a central fan helps cool the CPU zone passively by forced convection. This design enables controlled heating of the I/O region during system testing while maintaining cooler CPU temperatures for thermal separation and performance profiling.

An external controller governs heater power input, using an RTD sensor to provide real-time temperature feedback for closed-loop thermal control. The lid ensures safe operation by isolating heated surfaces from the upper housing using machined insulating layers.

---

## Skills Used

<div class="skills-list">
  <div class="skill">Thermal Architecture Design</div>
  <div class="skill">Flexible Heating Systems (Kapton)</div>
  <div class="skill">Passive and Forced Convection Cooling</div>
  <div class="skill">RTD Integration and Temperature Sensing</div>
  <div class="skill">Insulation and Heat Shielding</div>
  <div class="skill">Semiconductor Validation Hardware</div>
</div>

---

## Table of Contents
- [Design Purpose](#design-purpose)
- [Thermal Zones and Strategy](#thermal-zones-and-strategy)
- [Kapton Heater Integration](#kapton-heater-integration)
- [Fan Cooling Architecture](#fan-cooling-architecture)
- [RTD and Control System](#rtd-and-control-system)
- [Insulation and Mechanical Design](#insulation-and-mechanical-design)
- [Challenges and Considerations](#challenges-and-considerations)

---

## Design Purpose

This lid was developed to thermally stress the I/O zone of semiconductor devices during temperature-controlled testing, while avoiding unnecessary thermal loading on the CPU region. The design allows selective thermal input and rapid prototyping for system-level evaluations.

---

## Thermal Zones and Strategy

- **I/O Zone**: Actively heated using a Kapton film heater adhered to a heatsink.
- **CPU Zone**: Centrally cooled with a high-speed fan that forces ambient airflow across the component, simulating realistic airflow from in-system thermal environments.

---

## Kapton Heater Integration

A polyimide (Kapton) heater was selected for its thin profile, fast response time, and flexibility. It is mounted to the underside of a solid aluminum heatsink, which is thermally isolated from the lid chassis to prevent heat dissipation into non-targeted areas. Thermal tape ensures good contact while remaining replaceable for rapid iterations.

<img src="/_projects/HeaterLid/HeaterLidBottom.JPG" alt="Kapton-Heated Lid Assembly Bottom View" class="centered-image" />

---

## Fan Cooling Architecture

A DC axial fan is embedded in the center of the lid, positioned to blow vertically down onto the CPU die. This airflow helps prevent overheating during heater operation and maintains thermal isolation between zones.

---

## RTD and Control System

An RTD temperature sensor is mounted near the device under test in the I/O zone to provide accurate thermal feedback. An external PID controller adjusts power to the heater based on real-time readings, maintaining setpoints during long-duration tests.

---

## Insulation and Mechanical Design

A machined insulation barrier separates the heated heatsink from the top aluminum housing. Spring-loaded mounting elements ensure proper compression and alignment with test sockets, while minimizing mechanical loading on fragile package substrates.

---

## Challenges and Considerations

- Preventing heat soak into non-heated zones  
- Achieving stable setpoints despite airflow and environmental fluctuations  
- Managing electrical and thermal safety while retaining modularity  
- Minimizing lid mass while integrating insulation and control features  

