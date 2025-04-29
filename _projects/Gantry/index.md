---
layout: post
title: Pneumatic Gantry Test System
description: "A pneumatic benchtop fixture designed to reposition a heatpipe-based thermal lid over test boards, with custom adapter plates for alignment across varying board stackups and orientations."
card-image: /_projects/Gantry/Gantry.JPG
skills:
  - Pneumatics & Actuation
  - Mechanical Fixture Design
  - Mechanical Fasteners
  - Tolerance Stackup
  - Design for Manufacturability (DFM)
---

# Pneumatic Gantry Test System

<img src="/_projects/Gantry/Gantry.JPG" alt="Gantry System" class="centered-image" />

---

## Project Overview

The gantry system was developed to provide repeatable and accurate vertical actuation of a thermal lid assembly over customer test boards. It ensures reliable thermal contact while maintaining easy alignment and safe engagement, allowing customers to quickly run validation tests across different semiconductor packages.

---

## Skills Used

<div class="skills-list">
  <div class="skill">Pneumatics & Actuation</div>
  <div class="skill">Mechanical Fixture Design</div>
  <div class="skill">Mechanical Fasteners</div>
  <div class="skill">Tolerance Stackup</div>
  <div class="skill">Design for Manufacturability (DFM)</div>
</div>

---

## Table of Contents
- [Design Purpose](#design-purpose)
- [Pneumatic Actuation System](#pneumatic-actuation-system)
- [Adapter Plate Integration](#adapter-plate-integration)
- [Structural Frame and Movement](#structural-frame-and-movement)
- [Thermal Head Mounting](#thermal-head-mounting)
- [Board Compatibility and Stackup Handling](#board-compatibility-and-stackup-handling)
- [Challenges and Lessons Learned](#challenges-and-lessons-learned)

---

## Design Purpose

The gantry system was developed to provide repeatable and accurate vertical actuation of a thermal lid assembly over customer test boards. It ensures reliable thermal contact while maintaining easy alignment and safe engagement, allowing customers to quickly run tests on different packages for validation.

---

## Pneumatic Actuation System

The system features a main pneumatic cylinder for actuation, with two regulators controlling pressure ranges:
- Main cylinder (258–604 kgf)
- Pusher cylinder (65–153 kgf)

Vertically mounted pneumatic cylinders deliver controlled downward force to press the lid assembly against the test socket for partially-lidded devices.  
The actuation is user-triggered, with adjustable pressure settings (up to 70 psi) and an emergency safety stop button.  
Sensors on the main cylinder detect upper and lower positions, with LEDs indicating each limit.

---

## Adapter Plate Integration

Interchangeable adapter plates were designed to match different customer board sizes and orientations.  
- Maximum supported board size: **22.5 in × 22.5 in**  
- Plates are CNC-machined with custom cutouts and locating features for precise lid-to-board alignment.  
- Central support stiffener plates prevent board warpage during testing.

---

## Structural Frame and Movement

The gantry frame is constructed from machined aluminum and steel components for high rigidity.  
- The crossbeam supports the lid actuator assembly.
- Vertical motion along the Z-axis is stabilized using linear guide rails.
- Manual X-axis and Y-axis adjustment levers allow repositioning and locking of the actuator assembly relative to the board.

---

## Thermal Head Mounting

The gantry supports a passive heatpipe subassembly from previous lid solutions.  
- The thermal head is mounted to the actuator plate using quick-release hardware for easy swapping.
- Guide pins on the heatpipe pusher align precisely with socket base guide holes to maintain proper lid-to-socket registration.

---

## Board Compatibility and Stackup Handling

Multiple board thicknesses and socket configurations are supported by:
- Adjustable Z-height positioning
- Modular spacer kits
- Custom swappable adapter plates

This ensures consistent engagement and clamping force regardless of test board variations.

---

## Challenges and Lessons Learned

- Ensuring parallel actuation across large board footprints  
- Designing modular hardware adaptable to future thermal head geometries  
- Managing pneumatic forces for reliable engagement without risking fragile packages  
- Reducing setup time through a quick-change adapter plate system


