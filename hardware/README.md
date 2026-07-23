# Hardware

This directory contains the complete hardware design files for the **Posture Corrector using ATmega328P and MPU6050**.

The hardware was developed to provide a compact, low-cost, and wearable solution for real-time posture monitoring. A custom printed circuit board (PCB) was designed to integrate the microcontroller, motion sensor, power supply, and supporting circuitry into a single embedded system.

## Directory Structure

### 📂 Schematics
Contains the complete circuit schematic of the posture corrector, including the ATmega328P microcontroller, MPU6050 IMU, power supply, programming interface, and alert circuitry.

### 📂 PCB
Contains the PCB layout, routing, board design files, and 3D renderings used during the hardware development process.

### 📂 Gerbers
Contains the Gerber and drill files required for PCB fabrication.

### 📂 BOM
Contains the Bill of Materials (BOM) listing all electronic components used in the project, along with their specifications and quantities.

## Hardware Specifications

- **Microcontroller:** ATmega328P
- **Motion Sensor:** MPU6050 (3-axis Accelerometer + 3-axis Gyroscope)
- **Communication Protocol:** I²C
- **Alert Mechanism:** Buzzer / Vibration Motor
- **Power Supply:** Battery-powered
- **PCB Type:** Custom two-layer PCB

## Design Workflow

1. Circuit design and component selection
2. Schematic development
3. PCB layout and routing
4. Design Rule Check (DRC)
5. Gerber file generation
6. PCB fabrication
7. Component assembly and soldering
8. Hardware testing and validation

## Purpose

The hardware design demonstrates practical implementation of embedded electronics, including sensor interfacing, custom PCB design, power management, and wearable system development.
