# iot-telemetry-scale-pcb

# IoT Telemetry Scale – PCB Design

This repository contains the KiCAD design files for the custom PCB used in the **IoT Telemetry Scale** project – a modular, networked weighing solution originally built to monitor the weights of budgies in an aviary. 🐦📡

The PCB is built around the **ESP8266 (ESP12-E/F)** and the **HX711** load cell amplifier, aiming to be compact, reliable, and easily integrated with MQTT-based telemetry systems.

---

## ⚠️ Disclaimer / Flaws

> 🛠 **This PCB was specifically designed for a personal, non-commercial project.**  
> It is tailored to the requirements of my own bird scale setup and may not meet broader standards or needs out of the box.

- The layout was created to match a 3D-printed housing (available as a FreeCAD project in a separate repository), designed to fit **one feeding station** in our aviary. 
- The **load cell** used is a **non-standard part salvaged from a consumer coin scale**. Mounting holes and electrical characteristics may not match typical off-the-shelf sensors.
- The PCB was optimized for simplicity and personal ease of assembly, not for mass production or universal compatibility.

> **👉 Adapt to your needs!**  
> If you intend to use different load cells, microcontrollers (ESP32, for example), or housing dimensions, expect to modify the schematic and board layout accordingly.

---

## 💾 Files Included

- `*.kicad_sch` – KiCAD schematic file
- `*.kicad_pcb` – PCB layout
- `*.lib` / `*.mod` – Custom symbols and footprints (if applicable)

---

## 🔧 Requirements

- Used KiCAD Version is [9.0.1](https://www.kicad.org/) (project not guaranteed to open cleanly in earlier versions)
- Familiarity with ESP8266 / HX711 modules
- Soldering tools and basic electronics skills

---

## 📦 Suggested Components

- **Microcontroller:** ESP8266 (ESP-12E or ESP-12F module)
- **Load Cell Amplifier:** HX711
- **Power Supply:** 5V micro-USB or regulated supply (depending on build)
- **Load Cell:** Use a standard model, often sold with appropriate HX711 module altogether

Note: Adjust footprints and layout to your needs.

---

## 📸 Related Projects

- [iot-telemetry-scale](https://github.com/wbommel/iot-telemetry-scale) - Meta repository
- [iot-telemetry-scale-firmware](https://github.com/wbommel/iot-telemetry-scale-firmware) – Firmware for this board

---

## 📜 License

This project is open source under the MIT License.  
Feel free to fork, modify, and improve!

---

## 🙏 Acknowledgements

Special thanks to the open hardware community and the creators of KiCAD for making electronics design accessible to everyone.
