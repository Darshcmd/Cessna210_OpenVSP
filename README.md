# Cessna 210 (NASA Variant) — OpenVSP Aircraft Model

<div align="center">

![OpenVSP](https://img.shields.io/badge/OpenVSP-Aircraft%20Modelling-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Aerospace%20Design-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=for-the-badge)

**Parametric 3D reconstruction of the Cessna 210 (NASA Variant) using OpenVSP**  
*Indian Space Labs Winter Internship — Advanced Drone Technology | IIT Madras & ISRO*

</div>

---

## Table of Contents

- [Overview](#overview)
- [Software](#software)
- [Methodology](#methodology)
- [Aircraft Parameters](#aircraft-parameters)
- [Results](#results)
- [Repository Structure](#repository-structure)
- [Learning Outcomes](#learning-outcomes)
- [Author](#author)

---

## Overview

This project was completed as part of the **Indian Space Labs Winter Internship Training Program**, conducted under **IIT Madras and ISRO** in the domain of **Advanced Drone Technology**.

The objective was to **recreate the Cessna 210 (NASA Variant) aircraft geometry** using **OpenVSP** — an open-source parametric aircraft geometry modelling tool developed by NASA — working from 3-view engineering reference drawings and applying background image tracing for dimensional accuracy.

The project covers:
- Aircraft geometry interpretation from 2D engineering drawings
- Parametric component-level modelling in OpenVSP
- Structural decomposition: fuselage, wing, tail assembly, and propeller
- Cockpit-scale visualization using a human dummy reference model

---

## Software

| Tool | Description |
|------|-------------|
| **OpenVSP (Open Vehicle Sketch Pad)** | Open-source aircraft geometry modelling software developed by NASA |
| **Version** | Latest stable release |
| **Download** | [https://openvsp.org/](https://openvsp.org/) |

---

## Methodology

The model was built using the **background image tracing method** in OpenVSP — loading 3-view reference drawings (Top, Side, Front) as background images and constructing geometry over them.

### Step-by-Step Process

1. **Unit Configuration** — Set measurement units in OpenVSP for consistent scaling across all components.
2. **Reference Image Setup** — Loaded the 3-view aircraft drawing as a background reference in each viewport.
3. **Fuselage Modelling** — Used the **XSec Editor** to define and adjust cross-sectional profiles matching the fuselage outline.
4. **Main Wing** — Defined wing geometry using parameters: span, root chord, tip chord, taper ratio, sweep angle, and dihedral angle.
5. **Tail Assembly** — Modelled the **horizontal stabilizer** and **vertical tail** as separate wing geometries, scaled and positioned at the fuselage rear.
6. **Propeller** — Added propeller geometry at the aircraft nose.
7. **Human Dummy Model** — Placed inside the cockpit as a pilot-scale reference for cabin space visualization.

---

## Aircraft Parameters

All dimensions were **approximately estimated from the 3-view reference drawing** used during modelling.

### Wing

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
| Tail Taper | Gradual reduction toward rear |

### Tail Section

| Parameter | Value |
|-----------|-------|
| Horizontal Tail Span | ~4 m |
| Vertical Tail Height | ~2 m |

---

## Results

The final OpenVSP model successfully reconstructed the **Cessna 210 (NASA Variant)** geometry with the following outcomes:

- Accurate alignment of fuselage, main wing, and tail assembly
- Smooth aerodynamic surface continuity across all components
- Proportional scaling consistent with the 3-view reference drawings
- Cockpit-scale validation via human dummy placement
- Model exported as a `.vsp3` file ready for aerodynamic analysis, design iteration, or simulation workflows

---

## Repository Structure
```
cessna-210-openvsp/
│
├── model/
│   └── cessna_210_nasa.vsp3          # OpenVSP aircraft model file
│
├── screenshots/
│   ├── top_view.png
│   ├── side_view.png
│   └── front_view.png
│
├── references/
│   └── 3view_reference_drawing.*     # Reference images used for modelling
│
└── report/
    └── project_report.pdf            # Full internship project report
```

---

## Learning Outcomes

Through this project, the following competencies were developed:

- Interpreting 2D engineering drawings for 3D reconstruction
- Parametric aircraft geometry modelling in OpenVSP
- Understanding aircraft structural components and their spatial relationships
- Applying XSec-based fuselage design methodology
- Translating real-world aircraft reference data into simulation-ready 3D models

---

## Author

**Darsh Soni**  
B.Tech Computer Science Engineering (AI & Robotics) — VIT Chennai  
Indian Space Labs Winter Internship — Advanced Drone Technology  
Under **IIT Madras and ISRO**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-darshsoni04-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/darshsoni04)
[![GitHub](https://img.shields.io/badge/GitHub-Darshcmd-181717?style=flat&logo=github)](https://github.com/Darshcmd)

---

## License

This project is intended for **educational and internship purposes only**.  
All aircraft reference data is used strictly for academic modelling and learning.
