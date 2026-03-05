# Cessna 210 (NASA Variant) — OpenVSP Aircraft Model

<div align="center">

![OpenVSP](https://img.shields.io/badge/OpenVSP-Aircraft%20Modelling-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Aerospace%20Design-orange?style=for-the-badge)
![Internship](https://img.shields.io/badge/Internship-Indian%20Space%20Labs-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=for-the-badge)

**Parametric 3D reconstruction of the Cessna 210 (NASA Variant) using OpenVSP**

*Indian Space Labs Winter Internship — Advanced Drone Technology*  
*Program conducted under IIT Madras & ISRO*

</div>

---

# Table of Contents

- [Overview](#overview)
- [Project Objective](#project-objective)
- [Software Used](#software-used)
- [Methodology](#methodology)
- [Aircraft Parameters](#aircraft-parameters)
- [Results](#results)
- [Repository Structure](#repository-structure)
- [Learning Outcomes](#learning-outcomes)
- [Author](#author)
- [License](#license)

---

# Overview

This repository contains the **OpenVSP model of the Cessna 210 (NASA Variant)** created during the **Indian Space Labs Winter Internship Training Program** under **IIT Madras and ISRO**.

The goal of the project was to **recreate the aircraft geometry using OpenVSP** by studying **3-view engineering reference drawings** and applying **parametric modelling techniques**.

The project focuses on:

- Aircraft geometry reconstruction from reference drawings
- Parametric modelling using OpenVSP
- Understanding aircraft structural components
- Translating 2D design references into 3D geometry

The final model recreates the major aircraft components including:

- Fuselage
- Main Wing
- Horizontal Stabilizer
- Vertical Tail
- Propeller

Additionally, a **human dummy model was added inside the cockpit** to represent pilot scale and visualize cabin proportions.

---

# Project Objective

The primary objectives of this internship project were:

- To understand **aircraft geometry modelling using OpenVSP**
- To recreate a **real-world aircraft design from 3-view drawings**
- To learn **parametric modelling techniques used in aerospace design**
- To model major aircraft components including fuselage, wings, tail, and propeller
- To understand how aircraft proportions affect overall geometry

---

# Software Used

| Tool | Description |
|-----|-------------|
| **OpenVSP (Open Vehicle Sketch Pad)** | Open-source aircraft geometry modelling software developed by NASA |
| **Purpose** | Creating parametric aircraft models |
| **Download** | https://openvsp.org |

OpenVSP enables designers to **rapidly build and modify aircraft geometry** using parameter-based modelling.

---

# Methodology

The aircraft model was developed using the **Background Image Tracing Method** in OpenVSP.

### 1. Unit Configuration
Measurement units were configured in OpenVSP to ensure consistent scaling across all aircraft components.

### 2. Reference Image Setup
The **3-view aircraft drawing (Top, Side, Front)** was loaded as a **background reference image** inside OpenVSP.  
The image was aligned with coordinate axes and scaled appropriately.

### 3. Fuselage Modelling
The fuselage was created using **Fuselage Geometry** and edited using the **XSec Editor** to match the aircraft outline from the reference drawing.

### 4. Main Wing Creation
The main wing geometry was defined using key parameters:

- Wing span
- Root chord
- Tip chord
- Taper ratio
- Sweep angle
- Dihedral angle

The wing was positioned relative to the fuselage using the X and Z placement parameters.

### 5. Tail Assembly
Separate wing geometries were used to model the:

- Horizontal Stabilizer
- Vertical Tail

These were scaled appropriately and positioned at the rear of the fuselage.

### 6. Propeller Modelling
A propeller geometry was added at the **nose of the aircraft** and configured with suitable diameter and blade count.

### 7. Human Dummy Model
A **simple human dummy** was added inside the cockpit to act as a **scale reference for pilot seating and cockpit dimensions**.

---

# Aircraft Parameters

The aircraft dimensions were **approximately estimated using the 3-view reference drawing** used in the modelling process.

### Wing Parameters

| Parameter | Value |
|-----------|-------|
| Wing Span | ~11 m |
| Root Chord | ~1.6 m |
| Tip Chord | ~0.8 m |
| Taper Ratio | 0.5 |
| Sweep Angle | ~5° |
| Dihedral Angle | ~3° |

### Fuselage

| Parameter | Value |
|-----------|-------|
| Fuselage Length | ~8.6 m |
| Maximum Cabin Width | ~1.2 m |
| Tail Taper | Gradually reduced toward rear |

### Tail Section

| Parameter | Value |
|-----------|-------|
| Horizontal Tail Span | ~4 m |
| Vertical Tail Height | ~2 m |

---

# Results

The final OpenVSP model successfully reconstructed the **Cessna 210 (NASA Variant)** aircraft geometry.

Key outcomes of the project include:

- Accurate alignment of **fuselage, wings, and tail assembly**
- Smooth aerodynamic surface continuity
- Proper proportional scaling based on reference drawings
- Cockpit scale verification using the human dummy model

The aircraft model is saved as a **`.vsp3` file**, which can be used for:

- Aircraft geometry analysis
- Design modification
- Aerodynamic simulation workflows

---

# Learning Outcomes

Through this internship project, the following skills were developed:

- Aircraft geometry interpretation
- Parametric modelling in OpenVSP
- Understanding aircraft structural layout
- Fuselage design using cross-section editing
- Translating engineering reference drawings into 3D models

This project provided practical exposure to **aerospace design workflows used in aircraft conceptual modelling.**

---

# Author

**Darsh Soni**  
B.Tech Computer Science Engineering (AI & Robotics)  
VIT Chennai  

Indian Space Labs Winter Internship  
Advanced Drone Technology Program  

Conducted under **IIT Madras & ISRO**

GitHub: https://github.com/Darshcmd  
LinkedIn: https://linkedin.com/in/darshsoni04

---

# License

This project is intended for **educational and internship purposes only**.

Aircraft reference images and specifications were used strictly for **academic modelling and learning purposes**.
