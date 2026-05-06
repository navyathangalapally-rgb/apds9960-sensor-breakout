# APDS-9960 color Sensor PCB

This project involves the design and development of a custom PCB integrating an STM32 microcontroller with the APDS-9960 sensor for gesture, proximity, and color detection.

It was developed as part of laboratory work, focusing on sensor interfacing and embedded hardware design.


##  Overview

The goal of this project was to design a compact and reliable hardware system capable of interfacing with a multi-function sensor over I2C.

The system includes:
- STM32F103C8T6 microcontroller
- APDS-9960 gesture and color sensor
- Power regulation and USB interface

## How it Works

1. The APDS-9960 sensor detects gestures, proximity, and color data  
2. Communication is established via I2C protocol  
3. The STM32 processes the incoming sensor data  
4. The system can be extended for gesture-based control applications  


## Hardware Design

- Designed using **KiCad**
- Implemented stable **3.3V power supply**
- Proper decoupling capacitors added for noise reduction
- Clean PCB layout to ensure reliable signal routing


## Project Visuals

### 🔹 3D PCB Render
![3D PCB Render](3D%20PCB%20render.png)

### 🔹 Full Schematic
![Full Schematic](SCH-mc.png)

### 🔹 Sensor Interface (APDS-9960)
![Sensor Schematic](Sch-APDS-9960.png)

### 🔹 PCB Layout
![PCB Layout](footprint%20PCB.png)


## Tech Stack

- **Design Tool:** KiCad  
- **Microcontroller:** STM32F103C8T6  
- **Sensor:** APDS-9960  
- **Communication:** I2C  
- **Power:** 3.3V via Micro-USB  


## Repository Contents

- KiCad design files (`.kicad_pcb`, `.kicad_sch`, `.kicad_pro`)  
- PCB layout and schematic images  
- 3D model files  


## My Contribution

- Designed the schematic and PCB layout  
- Integrated STM32 with APDS-9960 sensor  
- Ensured stable power and proper signal routing  
- Validated the hardware design  

## Future Improvements

- Firmware implementation for real-time gesture recognition  
- Integration with robotics or automation systems  
- ROS-based sensor data publishing (future scope)


## Timeline

Developed as part of laboratory work (Dec 2024)
