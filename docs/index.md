# 🦖 Jurassic Rescue Robot – Portfolio Case Study

A university robotics project focused on designing, prototyping, and testing a robot for a Jurassic Park-themed rescue mission.

---

## 📌 Objective

Design a robot that:
- Autonomously presses a button to open a gate
- Manually retrieves a doll ("Ken") from a pit
- Optionally corrals dinosaur figures into a cage

---

## 🧠 Design Highlights

- **Autonomous Navigation** (no line following)
- **Button Pressing Mechanism** with limited DoF
- **Manual Rescue Arm** operated by gamepad
- **Multiple Mechanism Prototypes** (e.g., Plow, Clamp, Frying Pan)
- **Plow + Vertical Clamp** chosen for final implementation

---

## 🛠️ Constraints & Tools

| Category        | Constraint/Tool                                    |
|-----------------|----------------------------------------------------|
| Controller      | Raspberry Pi Pico                                  |
| Actuators       | Max 3 Servo Motors                                 |
| Design Limits   | No prefab chassis, minimal 3D printing allowed     |
| Programming     | MicroPython                                        |
| Planning Method | Scrum / Agile Sprints                              |
| Prototyping     | Cardboard mockups, CAD, 3D Printing, Laser Cutting |

---

## 📐 Design Process

### Round 1: Cardboard Prototyping
- Visualized lifting mechanism & bot dimensions
- Discovered the need for a retrieval arm
- Adjusted strategy to include reach-down capability

### Round 2: Motor & Sensor Integration
- Tested DC motors, servo movement, ultrasonic sensor
- Prototyped front wheel and spherical caster
- Designed initial CAD for 3D printing

### Round 3: Module Integration
- Combined electrical + mechanical components
- Built first mobile prototype using cardboard chassis
- Assembled spherical and front wheel modules

### Round 4: Closed-Loop Feedback & Autonomous Mode
- Battery monitor & control mode switching
- Encoders + PID for straight-line motion
- Started final presentation prep

### Round 5: Final Integration & Testing
- Merged all code into working file
- Practiced joystick control and tested on board
- Began autonomous button-press testing

---

## 🏆 Awards

🥇 **People’s Choice Award Winner**  
*Voted by peers and faculty for innovation and functionality.*

![Award](../assets/award.png)

---

## 📷 Robot Showcase

| Front View | Side View | Back View |
|------------|-----------|-----------|
| ![](../design/front.png) | ![](../design/side.png) | ![](../design/back.png) |

---

## 📂 Repository Structure

```bash
jurassic-rescue-robot/
├── code/
│   ├── Completed_Code.ino
│   └── Pico_WiFi_Gamepad.py
├── design/
│   ├── front.png
│   ├── side.png
│   ├── back.png
│   └── schematic.png
├── docs/
│   └── index.md      <-- This file
├── final_report/
│   └── final_report.pdf
├── README.md
└── requirements.txt
```

---

## 🔗 Explore More

- [📝 Final Report (PDF)](../final_report/final_report.pdf)
- [💡 View Code](../code/)
- [📐 View Designs](../design/)

---

> 🎓 Created as part of a university robotics design course.  
> Built with passion, planning, and more cardboard than you’d expect.