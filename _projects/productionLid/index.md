---
layout: post
title: Screw-Down Liquid-Cooled Lid
description: "A mechanically secured dual-zone thermal lid designed for semiconductor validation, featuring two independently cooled regions managed via a recirculating water chiller. Enables precise thermal control for partially-lidded LGA packages under varying power loads."
card-image: /_projects/productionLid/ProductionLid.JPG
skills:
  - Mechanical Design (Springs, Static FEA)
  - Cold Plate Design (FEA, CFD)
  - Manufacturing Processes (Welding, Machining)
  - Tolerance Stackup
  - Machine Drawings with GD&T
---

# Screw-Down Liquid-Cooled Lid

<img src="/_projects/productionLid/ProductionLid.JPG" alt="Dual-zone Screw-Down Lid" class="centered-image" />

---

## Project Overview

This project involved the development of a mechanically secured dual-zone thermal lid designed for high-power semiconductor device validation. Each zone, corresponding to the CPU and I/O regions of partially-lidded LGA packages, is independently cooled through dedicated internal water channels connected to a recirculating chiller.

The lid enables stable, isolated thermal control across the device under varying power loads while minimizing mechanical stress through precision fastening.

---

## Skills Used

<div class="skills-list">
  <div class="skill">Mechanical Design (Springs, Static FEA)</div>
  <div class="skill">Cold Plate Design (FEA, CFD)</div>
  <div class="skill">Manufacturing Processes (Welding, Machining)</div>
  <div class="skill">Tolerance Stackup</div>
  <div class="skill">Machine Drawings with GD&T</div>
</div>

---

## Table of Contents
- [Design Intent and Use Case](#design-intent-and-use-case)
- [Mechanical Fastening Approach](#mechanical-fastening-approach)
- [Thermal Architecture](#thermal-architecture)
- [Water Channel Design](#water-channel-design)
- [Simulation and Testing](#simulation-and-testing)
- [Assembly and DFM Considerations](#assembly-and-dfm-considerations)
- [Challenges and Lessons Learned](#challenges-and-lessons-learned)

---

## Design Intent and Use Case

The lid was developed to address thermal management challenges for partially-lidded LGA packages. It allows independent temperature control of both the central CPU region and the surrounding I/O area by setting inlet fluid temperature and flow rate via a recirculating water chiller.

---

## Mechanical Fastening Approach

Eight mechanical load points are utilized:
- Four outer fastening points anchor the lid to the socket housing.
- Four inner load cells (spring-loaded) provide compliant force between the CPU die and the middle thermal zone surface.

This approach ensures consistent, repeatable compression without over-constraining sensitive components.

---

## Thermal Architecture

The lid is thermally divided into two zones:
- **CPU Zone**: Central region designed to dissipate up to 350 W of heat.
- **I/O Zone**: Peripheral region capable of handling up to 180 W.

Each zone operates independently with its own cooling loop, maintaining strict temperature isolation and uniformity during device operation.

---

## Water Channel Design

Custom CNC-machined internal water channels optimize flow uniformity and minimize pressure drop. Key features:
- The I/O cooling block is fastened with screws and sealed via an O-ring interface.
- The CPU cooling block is welded directly to the CPU pedestal for higher thermal efficiency.
- Quick-disconnect fittings are installed for easy fluid line connection and maintenance.

---

## Simulation and Testing

Steady-state thermal and flow simulations (FEA and CFD) were conducted in ANSYS Icepak to validate heat extraction capability and minimize temperature gradients.  
Pressure drop analyses confirmed flow efficiency.  
Bench testing validated the thermal isolation between zones and system robustness.  
Findings were co-presented at **TestConX 2024**.

---

## Assembly and DFM Considerations

Designed for ease of manufacture and serviceability:
- Standard fasteners and sealing components were used where possible.
- Modular cooling blocks and standard socket compatibility ensured the design could adapt to multiple DUT setups and test benches.
- Special attention was given to weld quality and machined surface tolerances to guarantee thermal and mechanical reliability.

---

## Challenges and Lessons Learned

- Managing chiller capacity limits while reaching high operating temperatures (led to exploration of supplemental polyimide heater assist designs)
- Avoiding over-constraint of thermal contact while maintaining robust sealing
- Designing flexible, modular cooling loops to accommodate varying customer bench configurations
- Managing condensation during cold testing, prompting a modular purge kit development to maintain dry conditions
