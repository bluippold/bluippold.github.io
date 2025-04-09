---
layout: post
title: Gantry System
description: "A pneumatic benchtop fixture designed to reposition a heatpipe-based thermal lid over test boards, with custom adapter plates for alignment across varying stackups."
skills:
  - Pneumatics & Actuation
  - Mechanical Fixture Design
  - Mechanical Fasteners
  - Tolerance Stackup
  - Design for Manufacturability (DFM)
---

<img src="/_projects/Gantry/Gantry.JPG" alt="Gantry system CAD render" width="700" style="display: block; margin: 1.5rem auto; border: 1px solid #ccc; border-radius: 6px;" />

### Table of Contents
- [Design Purpose](#design-purpose)
- [Pneumatic Actuation System](#pneumatic-actuation-system)
- [Adapter Plate Integration](#adapter-plate-integration)
- [Structural Frame and Movement](#structural-frame-and-movement)
- [Thermal Head Mounting](#thermal-head-mounting)
- [Board Compatibility and Stackup Handling](#board-compatibility-and-stackup-handling)
- [Challenges and Lessons Learned](#challenges-and-lessons-learned)

---

### Design Purpose

The gantry system was developed to provide repeatable and accurate vertical actuation of a thermal lid assembly over customer test boards. It ensures reliable thermal contact while maintaining easy alignment and safe engagement, while allowing customer to quickly run tests on different packages for validation.

---

### Pneumatic Actuation System

There is a main cylinder for actuation with two regulators for the following: main cylinder (258-604kgf) and pusher cylinder (65-153kgf). Vertically mounted pneumatic cylinders deliver controlled downward force to press the lid assembly against the test socket for partially-lidded devices. The actuation is user-triggered, with an emergency safety button to stop and adjustable pressure settings for delicate package engagement (up to 70psi). There are two sensors on the main cylinder to adjust the up and down positions with LEDs indicating each limit. 

---

### Adapter Plate Integration

Interchangeable adapter plates were designed to match different customer board sizes and orientations. Available board size is 22.5in x 22.5in. Each plate was CNC machined with custom cutouts and locating features for precise lid-to-board alignment. Central area supported below the board with a stiffener plate to prevent warpage during testing.

---

### Structural Frame and Movement

The frame is constructed from machined aluminum and steel components for rigidity. The crossbeam holds the lid mount and actuator, while linear guides ensure stable, repeatable motion along the Z-axis without play or deflection. There are levers on the cylinder frame to move along the x-axis and lock into position and levers on the sides of the linear outer rails to move the pusher assembly along the y-axis.

---

### Thermal Head Mounting

The gantry supports a passive heatpipe subassembly used in prior lid solutions. It is mounted to the actuator plate with quick-release hardware, allowing rapid swaps and consistent contact during test cycles. There are guide pins on the heatpipe pusher to align with socket base guide holes for proper alignment.

---

### Board Compatibility and Stackup Handling

Multiple board thicknesses and socket configurations are supported through adjustable Z-height, spacer kits, and swappable adapter plates. The design ensures consistent clamping pressure regardless of stackup variations or changes in standoffs.

---

### Challenges and Lessons Learned

- Ensuring parallel actuation over large board footprints  
- Designing modular hardware that could adapt to future lid geometries  
- Managing pneumatic force to balance reliability with safety  
- Reducing setup time through quick-swap adapter design


