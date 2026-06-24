# 🤖 Rope-Climbing Robot with End Detection

> **Embedded Systems & LEGO Mechatronics Project**  
> Built with Husarion CORE2
---
## 🔗 Project Files

The video of robot is available here:  
👉 [View on Google Drive](https://drive.google.com/file/d/1LeJXvlAE3gpKTVCMAmB0CtVtIrfMwhCH/view)

---

## 📋 Project Description

This project focuses on designing and building a **robot capable of autonomously climbing a vertical rope**, constructed entirely from **LEGO blocks**. The robot detects the end of the line at the bottom and the ceiling at the top, stops accordingly, and reverses direction.

The main control module is the **Husarion CORE2** driver, which coordinates sensor inputs, motor control, and the anti-slip logic.

The system integrates:
- **Mechanical design** — LEGO structure & rope gripping mechanism
- **Embedded programming** — firmware written in C++ using hFramework
- **Sensor-motor coordination** — closed-loop control with encoder feedback

---

## 🎯 Project Goal

The primary objective was to design, build, and program a robot that:

- Climbs a vertical rope using a LEGO-based mechanism
- Detects the **bottom end of the line** and the **ceiling at the top**
- Responds to sensor signals — stops and reverses direction
- Prevents rope slippage through a dedicated mechanical & software system

> Pre-built climbing mechanisms were not used — the full system was integrated from scratch, from mechanical design to firmware.

---

## 🛠️ Technology Stack

| Component | Role |
|---|---|
| **Husarion CORE2** | Main controller (STM32F4 ARM Cortex-M4 @ 168 MHz) |
| **C++ / hFramework** | Motor drivers, sensor polling, control loops |
| **LEGO Technic** | Structural chassis, rope-gripping wheel assembly |
| **DC motors + encoders** | Closed-loop climbing control |
| **Limit / proximity sensors** | End-of-line and ceiling detection |
---



