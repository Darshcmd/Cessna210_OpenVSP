# Cessna 210 (NASA Variant) – OpenVSP Aircraft Model

## Indian Space Labs Winter Internship Project

This project was completed as part of the **Indian Space Labs Winter Internship Training Program** conducted under **IIT Madras and ISRO** in the domain of **Advanced Drone Technology**.

The objective of this internship project was to **recreate the Cessna 210 (NASA Variant) aircraft geometry using OpenVSP**, an open-source parametric aircraft modeling software developed by NASA.

The project focuses on understanding **aircraft geometry modelling, parametric design, and aircraft component structures** using engineering reference drawings.

---

# Project Overview

The aircraft model was created in **OpenVSP** using **3-view reference drawings (Top, Side, and Front views)** and the **background image tracing method**.

The following aircraft components were modeled:

- Fuselage
- Main Wing
- Horizontal Tail
- Vertical Tail
- Propeller

A **simple human dummy model** was also added inside the cockpit to provide a **scale reference for pilot seating and cockpit space visualization**.

---

# Software Used

**OpenVSP (Open Vehicle Sketch Pad)**  
An open-source aircraft geometry modeling tool developed by **NASA**.

Download: https://openvsp.org/

---

# Methodology

The aircraft model was created using the **background image tracing technique** in OpenVSP.

1. The measurement units were configured in OpenVSP to maintain consistent scaling.
2. The provided **3-view aircraft drawing** was loaded as a **background reference image**.
3. The fuselage was created using the **XSec Editor** by adjusting cross-sections to match the aircraft outline from the reference image.
4. The main wing was created by setting parameters such as **span, root chord, tip chord, taper ratio, sweep angle, and dihedral angle**.
5. Separate wing geometries were used to design the **horizontal tail and vertical tail**, which were scaled and positioned at the rear of the fuselage.
6. A **propeller geometry** was added at the nose of the aircraft.
7. A **human dummy model** was placed inside the cockpit to represent pilot scale.

---

# Aircraft Parameters Used

The aircraft dimensions were **approximately estimated from the 3-view reference drawing** used during modelling.

### Wing Parameters

| Parameter | Value |
|----------|------|
| Wing Span | ~11 m |
| Root Chord | ~1.6 m |
| Tip Chord | ~0.8 m |
| Taper Ratio | 0.5 |
| Sweep Angle | ~5° |
| Dihedral Angle | ~3° |

### Fuselage

| Parameter | Value |
|----------|------|
| Fuselage Length | ~8.6 m |
| Maximum Cabin Width | ~1.2 m |
| Tail Taper | Gradually reduced towards rear |

### Tail Section

| Parameter | Value |
|----------|------|
| Horizontal Tail Span | ~4 m |
| Vertical Tail Height | ~2 m |

---

# Results

The final OpenVSP model successfully recreated the **Cessna 210 aircraft geometry**.

Key outcomes:

- Correct alignment of **fuselage, wings, and tail**
- Smooth aerodynamic surface geometry
- Proper proportional scaling based on reference drawings
- Addition of a **human dummy model** to represent cockpit scale

The aircraft model is saved as a **`.vsp3` file**, which can be further used for **aerodynamic analysis, design modification, and simulation in OpenVSP**.

---

# Deliverables

This repository contains the following files:

- OpenVSP aircraft model file (`.vsp3`)
- 3-view screenshots of the aircraft model
  - Top View
  - Side View
  - Front View
- Project report document
- Reference images used for modelling

---

# Learning Outcomes

Through this internship project, the following skills were developed:

- Aircraft geometry interpretation
- Parametric aircraft modeling
- Using OpenVSP for aerospace design
- Understanding aircraft structural components
- Converting 2D engineering drawings into 3D models

---

# Author

**Darsh Soni**

Indian Space Labs  
Winter Internship Training Program  
Advanced Drone Technology  

Under **IIT Madras and ISRO**

---

# License

This project is for **educational and internship purposes only**.
