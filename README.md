# Design-and-Development-of-a-Remote-Controller-for-an-RC-Vehicle
Custom microcontroller-based remote controller for an RC vehicle, featuring ESP32-C3, nRF24L01 wireless communication, TFT display, dual analog joysticks, programmable buttons, Li-Po battery management, USB-C charging, and integrated power regulation.

# Remote Controller for RC Vehicle 🎮

![Project Banner](images/3d-render.png)

[![Hardware](https://img.shields.io/badge/Hardware-KiCad-blue.svg)](https://www.kicad.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()

A custom remote control hardware project designed for radio-controlled (RC) vehicles. This repository contains the complete design cycle: schematic, PCB layout, documentation, and manufacturing outputs.

---

## 🌟 Key Features

* **Wireless Communication:** [e.g., 2.4 GHz NRF24L01+ / ESP-NOW / ExpressLRS] with up to [X] meters range.
* **Control Inputs:** 2 dual-axis gimbals, [X] toggle switches, and [Y] potentiometers.
* **Display:** [e.g., 0.96" OLED I2C / 1.8" TFT] for telemetry and battery status.
* **Power System:** [1S/2S] Li-Po battery with built-in USB-C charging circuitry.
* **Ergonomics:** Compact double-sided PCB optimized for 3D-printed enclosures.

---

## 🛠 Specifications

| Feature | Specification |
| :--- | :--- |
| **Microcontroller** | [e.g., ESP32 / STM32F103 / ATmega328P] |
| **RF Module** | [e.g., NRF24L01+ PA/LNA] |
| **Operating Frequency** | 2.4 GHz |
| **Supply Voltage** | 3.7V - 4.2V (Li-Po) |
| **Charging Interface** | USB Type-C (TP4056) |
| **Board Dimensions** | [e.g., 100 x 60 mm] |
| **PCB Layer Count** | 2 Layers (Double-sided) |

---

## 📂 Repository Structure

```text
├── docs/             # Schematics (PDF), datasheets, and technical specs
│   └── schematic.pdf
├── hardware/         # CAD project files (KiCad/Altium) & Gerber files
│   ├── gerber/       # Manufacturing output files
│   └── project/      # Source PCB layout files
├── images/           # Renders, PCB photos, and diagrams
│   ├── 3d-render.png
│   ├── pcb-top.png
│   └── pcb-bottom.png
└── README.md         # Project overview