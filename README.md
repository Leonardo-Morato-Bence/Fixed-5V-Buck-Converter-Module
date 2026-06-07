# Fixed-5V-Buck-Converter-Module
Compact high-efficiency DC-DC buck converter module. LM2596S-5.0 regulator, 33μH inductor and SS54 Schottky diode to provide a stable 5V  output.

<img width="956" height="545" alt="image" src="https://github.com/user-attachments/assets/c8f0b8dd-e292-426e-b03c-63381092813c" />

---

## Overview

This project implements a compact fixed-output DC-DC buck converter capable of converting input voltages from 7V to 25V into a regulated 5V output.

The design is based on the LM2596S-5.0 switching regulator and includes a carefully selected power stage consisting of a 33µH inductor, SS54 Schottky diode, and filtering capacitors.

The module is suitable for embedded systems, industrial control equipment, sensors, microcontrollers, and educational power electronics applications.

---

## Features

- Input voltage range: 7V to 25V DC
- Fixed regulated 5V output
- LM2596S-5.0 switching regulator
- Up to 2A continuous output current
- Up to 3A peak output current
- High conversion efficiency
- Low output ripple
- SS54 Schottky rectifier
- 33µH power inductor
- Input and output filtering capacitors
- Power status LED
- Screw terminal connections
- Compact PCB design

---

## Applications

- Embedded systems
- Microcontroller projects
- Industrial automation
- Sensor power supplies
- Battery-powered devices
- Educational power electronics projects
- General-purpose 5V power conversion

---

## Technical Specifications

| Parameter | Value |
|------------|------------|
| Input Voltage | 7V – 25V |
| Output Voltage | 5V |
| Continuous Output Current | 2A |
| Peak Output Current | 3A |
| Efficiency | Up to 80% |
| Output Ripple | 30–50 mVpp |
| Switching Regulator | LM2596S-5.0 |
| PCB Dimensions | 64.9 mm × 34.5 mm |

---

## System Architecture

<img width="761" height="314" alt="image" src="https://github.com/user-attachments/assets/8ab2f9db-a90b-4d05-8866-8b22988fece6" />

---

## Design Highlights

### Efficient Power Conversion

The LM2596 switching regulator provides:

- High conversion efficiency
- Reduced heat dissipation
- Wide input voltage compatibility
- Reliable operation under varying loads

### Power Stage

The converter power stage consists of:

- LM2596S-5.0 regulator
- 33µH power inductor
- SS54 Schottky diode
- Bulk filtering capacitors

This combination ensures stable output voltage and low ripple operation.

### Protection Features

The LM2596 includes:

- Thermal shutdown protection
- Internal current limiting
- Short-circuit protection

These features improve system reliability and robustness.

---

## Main Components

| Component | Function |
|------------|------------|
| LM2596S-5.0 | Buck regulator |
| SS54 | Schottky rectifier |
| DR125-330 (33µH) | Power inductor |
| 220µF Capacitors | Input/output filtering |
| LED Indicator | Output status |

---

## Hardware Images

### 3D

<img width="1067" height="551" alt="image" src="https://github.com/user-attachments/assets/f34a2221-cc00-43c6-a4db-e65759905cec" />

### PCB Top Side

<img width="1009" height="538" alt="image" src="https://github.com/user-attachments/assets/efbfd906-66a3-482b-b016-b8910f025f53" />

### PCB Bottom Side

<img width="998" height="540" alt="image" src="https://github.com/user-attachments/assets/593f935f-d742-4bf5-8cb9-4ff86cb5167a" />

---

## Electrical Characteristics

| Parameter | Min | Typ | Max |
|------------|------------|------------|------------|
| Input Voltage | 7V | — | 25V |
| Output Voltage | 4.9V | 5.0V | 5.1V |
| Output Current | — | 2A | 3A |
| Efficiency | — | 80% | — |
| Ripple Voltage | — | 30mVpp | 50mVpp |

---
