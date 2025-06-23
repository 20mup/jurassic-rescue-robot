# 🧠 Code Overview — Jurassic Rescue Robot

This folder contains the core codebase for our autonomous + manual control robot built with the Raspberry Pi Pico.

---

## 📂 Files

### `pico_main_control.ino`
- ⚙️ Arduino-style program uploaded to the Raspberry Pi Pico
- Receives joystick commands via WiFi (UDP)
- Controls:
  - Motors (via H-bridge)
  - Servos for claw/lifting mechanism
  - Ultrasonic sensor for autonomous navigation
  - Battery monitoring
- Includes logic for closed-loop feedback using motor encoders + PID control

---

### `gamepad_input_udp.py`
- 🕹️ Python script that runs on the host PC
- Reads gamepad input using the `inputs` package
- Sends encoded UDP packets to the robot’s IP address
- Supports:
  - Joystick X/Y axes
  - All buttons and triggers
  - Mode switching (manual vs autonomous)

> 🔧 Ensure your gamepad is in **XInput mode** and your PC is on the same WiFi network as the Pico.

---

## 🛠️ Setup Notes

- The Pico and the host machine must be connected to the **same network**
- The IP address in `gamepad_input_udp.py` must match the Pico’s assigned address
- Use `Thonny` or Arduino IDE to upload `.ino` code to the Pico
- Install Python dependencies:
  ```bash
  pip install inputs
  ```

---

## 🔄 Data Flow

```
Gamepad → PC (Python) → UDP → Raspberry Pi Pico → Motors / Servos / Sensors
```

---

## 📎 Dependencies

- Python 3.x
- [`inputs`](https://pypi.org/project/inputs/) (for reading gamepad input)
- Arduino/Thonny IDE for Pico code upload

---

## 👨‍💻 Authors

- Mousa Pirzada — Python + Embedded Logic
- Kaitlyn — Electronics + Hardware Integration

