---
title: "Supersonic Flow over a Diamond Airfoil"
date: 2024-05-01
summary: "Implementation of a 2D finite-volume Euler solver with AUSM+up scheme to capture oblique shock waves on a diamond airfoil."
tags:
  - CFD
  - Numerical Methods
  - Aerodynamics
links:
  - name: PDF Report
    url: Euler_CFD_Project.pdf
image:
  filename: thumbnail.png
  caption: "CFD simulation showing oblique shock formation."
---

**Overview:**  
Computational Fluid Dynamics is a fundamental topic in engineering, allowing us to simulate real-world scenarios computationally with the help of numerical methods. This project implements a supersonic flow over a diamond-shaped airfoil surface using a 2D Euler solver with finite volume formulation.  

The solver was developed in two stages:
- A **first-order AUSM+up** scheme  
- A **higher-order TVD MUSCL formulation**  

The solver successfully captures **oblique shock waves** generated at the airfoil’s leading edge and compares results (wave angle, Mach number, pressure and temperature ratios) with analytical solutions.  

### Results
- Solver captured **leading-edge oblique shocks** accurately.  
- Verified **wave angles and pressure ratios** against analytical data.  
- Demonstrated improvement moving from **first-order AUSM+up** to **MUSCL** scheme.  

📄 Full report: [Download here](Euler_CFD_Project.pdf)

