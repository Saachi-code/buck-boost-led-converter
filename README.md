**Title:** Implementing Dual-Switch Non-Inverting Buck-Boost Converters for Optimized LED Lighting Systems  
**Authors:** Saachi Jaiswal,Hajira Naim  
**Date:** December 2023  

---

## 📖 Summary
This project implements and analyzes a **dual-switch non-inverting buck-boost converter** for LED and fluorescent lighting applications.

- Converter designed to work in **Continuous Conduction Mode (CCM)**.  
- Controlled using **PWM regulation** and a **Type-III rational controller**.  
- Ensures compatibility with both **LED drivers** and **electronic ballasts**.  
- Simulated and validated in **MATLAB Simulink**.  

---

## ⚡ Features
- Buck mode: step-down when input > load voltage.  
- Boost mode: step-up when input < load voltage.  
- Buck-Boost mode: automatic switching between buck & boost.  
- Efficient and stable across varying load conditions.  

---

## 📂 Repository Structure
- `201_Final_Report.pdf` → Complete writeup (theory, design, simulation results)  
- `simulink/` → Simulink project files in three stages:  
  - `ProjectPart1.slx` – initial buck/boost circuit  
  - `ProjectPart2.slx` – controller integration & analysis  
  - `Main_Project.slx` – final integrated converter (200V/400V input → 280V output)  
