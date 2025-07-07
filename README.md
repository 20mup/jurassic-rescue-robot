# 🦖 Jurassic Rescue Robot

A semi-autonomous rescue robot developed for the **MREN 303: Mechatronics Design** course at Queen’s University. Designed to traverse a gameboard, press a gate-opening button autonomously, and manually retrieve a "Ken" doll while clearing the "dinosaur" figures under strict hardware constraints.

![Robot Front View](images/robot_front.jpg)

---

## 🏆 Awards

> 🥇 **People’s Choice Award** – Voted best design and execution by peers and faculty.

---

## 📸 Gallery

| Front | Side | Back |
|-------|------|------|
| <img src="images/robot_front.jpg" width="250"/> | <img src="/images/robot_side.jpg" width="250"/> | <img src="/images/robot_back.jpg" width="250"/> |

| Award | Circuit | Gameboard |
|-------|---------|-----------|
| <img src="/images/award_robot.jpg" width="250"/> | <img src="/images/electrical_schematic.png" width="250"/> | <img src="/images/gameboard_middle.webp" width="250"/> |

---

## 🚀 Project Overview

Built for Queen’s University’s **Tronassic Park Competition**, this robot combined autonomous and manual control to complete a two-phase mission:
- **Phase 1:** Autonomously press a button to open a gate.
- **Phase 2:** Switch to joystick control to retrieve a toy figure from a pit.

---

## 🧩 Problem / 💡 Solution

**Problem:** Navigate an uneven gameboard, press a button accurately, and retrieve an object — all using only 3 servo motors and custom electronics.  
**Solution:** A compact, dual-mode robot using ultrasonic alignment and DC motor encoders, with a front clamp to lift the target figure like a forklift.

---

## ✨ Key Features

- Autonomous navigation using ultrasonic sensors
- Manual control via joystick (Arduino + Pico W)
- Closed-loop motor feedback with DC encoders
- Custom 3D-printed chassis and laser-cut wheels
- Integrated power management (voltage dividers)
- Emergency override via controller

---

## 💻 Tech Stack

| Area              | Tools / Tech                      |
|-------------------|-----------------------------------|
| Microcontroller   | Raspberry Pi Pico W, Arduino      |
| Programming       | MicroPython, Arduino C++          |
| CAD & Fabrication | SolidWorks, laser cutting, 3D printing |
| Communication     | USB Serial, Joystick              |

---

## 📁 Project Structure

```bash
JurassicRescueRobot/
├── code/                   # MicroPython + Arduino scripts
├── design/                 # CAD files (.SLDPRT, .STL, .DXF)
├── images/                 # Robot photos & schematics
├── docs/                   # Engineering case study & final report
└── README.md
```

---

## 👥 Team

- **Mousa Pirzada** – Lead Programmer: Pico W scripting, encoder feedback, integration.
- **Kaitlyn Johnston** – Electrical + Mechanical: Circuit design, CAD, fabrication.

---

## 📖 Learn More

- [📂 CAD Files & Build Details](https://github.com/20mup/JurassicRescueRobot/tree/main/design)
- [📄 Engineering Case Study](docs/jurassic-rescue-case-study.md)

---

> _Built with gears, wires, and the spirit of Jurassic Park._ 🦕
