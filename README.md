# 🛰️ APDS-9960 Gesture Sensor Project

Hey there! This is a project I worked on in the **CBMC Laboratory**. It's a custom-designed PCB that uses an **STM32** microcontroller to talk to an **APDS-9960** sensor—which is a cool little chip that can detect colors, proximity, and even hand gestures!

---

## 📸 What does it look like?

*(If these images aren't showing up, you can find them in the file list above!)*

### 1. The 3D Render
This is how the board is designed to look once it's manufactured. I've included a Micro-USB port for easy power and programming.
![Board 3D View](3D%20PCB%20render.png)

### 2. The Brains (STM32 Schematic)
This shows how the STM32F103 (the "brain") is wired up to the power supply and the USB port.
![STM32 Schematic](SCH-mc.jpg)

### 3. The Sensor (APDS-9960)
A closer look at how the gesture sensor is connected via the I2C protocol.
![Sensor Detail](Sch-APDS-9960.png)

### 4. The PCB Layout
The "X-ray" view of the copper traces and component placements.
![PCB Layout](footprint%20PCB.jpg)

---

## 🛠️ Tech Stack
* **Design Tool:** KiCad (Open Source EDA)
* **MCU:** STM32F103C8T6 
* **Sensor:** Broadcom APDS-9960
* **Power:** 3.3V via Micro-USB

## 📂 What's in this Repo?
* **Design Files:** All the KiCad source files (`.kicad_pcb`, `.kicad_sch`) so you can edit the design yourself.
* **3D Models:** The `.step` file for the sensor so you can see it in 3D.
* **Snapshots:** Pictures of the schematic and layout for quick viewing.

---
*Developed as part of the project laboratory data, Dec 2024.*
