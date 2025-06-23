# 🦖 Jurassic Rescue Robot — Portfolio Case Study

## Overview

The Jurassic Rescue Robot was a semester-long robotics project where we designed, prototyped, and tested an autonomous and manually operated robot tasked with completing a Jurassic Park-themed rescue mission. The final robot could autonomously press a button to open a gate and manually retrieve a doll (Ken) from a pit while optionally corralling dinosaur figures.

> 🏆 **Awarded People's Choice Award** for best project execution and presentation.

---

## 💡 Project Goals

* Build a robot capable of autonomous and manual operations
* Retrieve a figure (Ken) from a simulated pit
* Press a button autonomously to open a gate
* Optionally corral dinosaur figures for extra points
* Meet specific mechanical and electrical constraints

---

## 🔧 Engineering Constraints

* **Microcontroller**: Raspberry Pi Pico
* **Motor Limit**: Max 3 servo/DC motors
* **Fabrication**: Limited laser cutting and 3D printing
* **No prefab chassis**: Custom frame required
* **Manual & Autonomous**: Robot had to support both modes

---

## 🛠 Design Process

### Round 1 – Concept + Cardboard Prototypes

* Brainstormed multiple rescue mechanisms (plow, claw, scoop)
* Tested with cardboard mockups to visualize robot dimensions and lifting methods
* Identified the need for a vertically-oriented claw for pit retrieval

### Round 2 – Electrical + Mechanical Foundation

* Integrated motor drivers, servo motors, and ultrasonic sensors
* Built initial CAD models for the chassis and 3D printed key components
* Created laser cut wheels and initial control logic for motors and sensors

### Round 3 – Subsystems Integration

* Designed power budget and schematic
* Created and tested spherical rear wheel + motorized front wheels
* Combined code into one file with joystick control and encoder support

### Round 4 – Prototype Testing + Sustainability

* Assembled full prototype chassis
* Created switching logic between autonomous/manual modes
* Implemented battery monitoring system
* Considered long-term sustainability: energy efficiency and minimal emissions

### Round 5 – Competition Prep

* Developed autonomous logic to navigate using ultrasonic sensors
* Tested robot on the gameboard and refined performance
* Finalized presentation and documentation

---

## 🤖 Final Design Features

* **Manual Control**: Joystick-operated movement with closed-loop feedback
* **Autonomous Mode**: Ultrasonic-based button navigation
* **Lifting Mechanism**: Claw for rescuing figure from pit
* **Chassis**: Custom hybrid of 3D-printed and laser cut parts
* **Caster Wheel**: Spherical wheel enabled multidirectional movement

---

## 🧠 Key Technologies Used

* Python (Raspberry Pi Pico scripts)
* C++ (Arduino-based logic)
* SolidWorks (CAD modeling)
* Laser Cutting + 3D Printing
* Ultrasonic Sensors, Servo & DC Motors

---

## 📸 Media Gallery

> *Available in `/design/` and `/images/` folders in repo.*

* Front, side, and back views of robot
* Design evolution (cardboard → 3D print → final)
* Circuit schematic
* Presentation and poster screenshots

---

## 📝 Lessons Learned

* Prototyping early with cardboard saved mechanical rework
* Encoder calibration and closed-loop feedback significantly improved drive accuracy
* Mechanical tolerances (wheel shaft fit) directly affected robot movement
* Collaborative planning via Scrum ensured iterative, functional builds

---

## 🎓 Team Contributions

**Mousa Pirzada**: Lead programmer, autonomous logic, CAD design, closed-loop systems, documentation
**Kaitlyn \[Last Name]**: Hardware integration, laser cutting, wiring, team health lead

---

## 🏁 Outcome

The final robot successfully completed all base objectives and demonstrated autonomous gate interaction. The project was recognized with the **People’s Choice Award** at the course showcase for outstanding teamwork, innovation, and presentation.

---

## 🔗 Repository Highlights

* `/code/` — All Python and Arduino scripts
* `/design/` — Design files, photos, and schematics
* `/docs/` — Final report and case study
* `/images/` — Media used in documentation and README

> ⭐ **This project reflects our ability to integrate mechanical design, embedded programming, and iterative prototyping into a real-world robotics challenge.**
