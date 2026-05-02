# APDS-9960 & STM32 Gesture Sensor Breakout

This repository contains the KiCad design files for a custom PCB featuring the **APDS-9960** (RGB, Proximity, and Gesture sensor) controlled by an **STM32F103C8T6** microcontroller.

## Project Visuals

### 3D PCB Render
This is the final look of the board, including the sensor placement and Micro-USB interface.
![3D PCB Render](3D%20PCB%20render.png)

### Schematic Design
The circuit includes the STM32 core, voltage regulation, and the I2C communication lines for the sensor.

* **Main System Schematic:**
![Full Schematic](SCH-mc.jpg)

* **APDS-9960 Sensor Detail:**
![Sensor Schematic](Sch-APDS-9960.png)

### PCB Layout & Footprints
The 2D layout showing trace routing and component footprints.
![PCB Footprint](footprint%20PCB.jpg)

## Features
* **Sensor:** APDS-9960 for gesture and color sensing.
* **MCU:** STM32F103 (Blue Pill compatible core).
* **Interface:** Micro-USB for power and programming.
* **Form Factor:** Compact design with M3 mounting holes.

## How to Use
1. Clone this repository.
2. Open `proj_cbmc_lab.kicad_pro` in KiCad.
3. View the schematic or PCB layout to modify the design.
