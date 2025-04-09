---
layout: post
title: Screw-Down Liquid-Cooled Lid
description: "A mechanically secured thermal lid for semiconductor testing, featuring two independently cooled zones controlled via a recirculating water chiller for precise, isolated temperature management."
skills: 
- Mechanical Design (Springs, Static FEA)
- Cold Plate Design (FEA, CFD)
- Manufacturing Processes (Welding, Machining)
- Tolerance Stackup
- Machine Drawings with GD&T
---

<img src="/projects/productionLid/ProductionLid.JPG" alt="Dual-zone screw-down lid render" width="700" style="display: block; margin: 1.5rem auto; border: 1px solid #ccc; border-radius: 6px;" />

### Table of Contents
- [Design Intent and Use Case](#design-intent-and-use-case)
- [Mechanical Fastening Approach](#mechanical-fastening-approach)
- [Thermal Architecture](#thermal-architecture)
- [Water Channel Design](#water-channel-design)
- [Simulation and Testing](#simulation-and-testing)
- [Assembly and DFM Considerations](#assembly-and-dfm-considerations)
- [Challenges and Learnings](#challenges-and-learnings)

---

### Design Intent and Use Case

Developed for partially-lidded LGA packages requiring independent thermal control over both regions (CPU and I/O). Using a recirculating water chiller, the user can set an inlet temperature and flow rate to achieve their desired operating temperature on the package under different power loads. 

---

### Mechanical Fastening Approach

There are eight total load cells: four outer load cells to mount the lid to the socket housing and four inner load cells that act as springs between both zone surfaces for when the middle zone contacts the exposed CPU die. 

---

### Thermal Architecture

The lid is divided into two thermally independent zones: a central CPU zone and an outer I/O zone. The CPU zone is designed to handle power loads up to 350W, while the surrounding I/O zone supports up to 180W. Each zone contains an independent fluid channel, acting as two separate cold plates.

---

### Water Channel Design

Custom internal water channels are CNC-machined into the body of the lid, optimized for flow uniformity and minimal pressure drop. The I/O fluid block is fastened via screws to the I/O pedestal and an O-ring is used to seal this channel. The CPU fluid block is welded to the CPU pedestal containing the water channels. Both zones have quick disconnect fittings at the inlet and outlet for easy removal and insertion. 

---

### Simulation and Testing

I conducted steady-state FEA and CFD simulations in ANSYS Icepak to optimize the thermal performance of this product and to validate temperature gradients. Pressure drop analysis was also conducted to verify flow efficiency. On-bench testing confirmed thermal isolation and uniformity across zones, and I co-presented these findings at TestConX 2024. 

---

### Assembly and DFM Considerations

The lid was designed for machinability and modular assembly, using off-the-shelf fasteners and standard seals. Mounting geometry was kept compatible with a variety of socket housings and PCB stackups.

---

### Challenges and Learnings

- Reaching high temperatures with the use of a chiller put significant strain on it, designing similar product that uses a polymide heater to help  
- Avoiding over-constraining contact points while maintaining seal integrity  
- Designing flexible cooling loops to fit varying bench configurations
- In cold temperature testing, the top lid surfaces experience condensation; designed a modular purge kit that fits on top of the lid

---
