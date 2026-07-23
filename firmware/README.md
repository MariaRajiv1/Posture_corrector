# Firmware

This directory contains the firmware developed for the **Posture Corrector using the ATmega328P and MPU6050**.

The firmware is responsible for acquiring motion data from the MPU6050 IMU, processing the sensor readings to determine the user's posture, and activating an alert when poor posture is maintained beyond a predefined threshold. The software is optimized for real-time operation on the ATmega328P microcontroller.

---

## Features

- Real-time posture monitoring
- MPU6050 accelerometer and gyroscope interfacing
- I²C communication with the IMU
- Sensor data processing
- Posture angle calculation
- Configurable posture threshold
- Timer-based slouch detection
- Alert generation using a buzzer or vibration motor

---

## Development Environment

- **Microcontroller:** ATmega328P
- **Programming Language:** Embedded C/C++
- **Development Platform:** Arduino IDE
- **Communication Protocol:** I²C

---

## Firmware Workflow

1. Initialize the ATmega328P and MPU6050.
2. Read accelerometer and gyroscope data from the IMU.
3. Process the sensor data to determine the user's orientation.
4. Compare the measured posture with the predefined threshold.
5. If poor posture persists for the specified duration, activate the alert mechanism.
6. Continue monitoring until the posture returns to the acceptable range.

---

## Source Code

The firmware source code is provided in this directory and can be compiled and uploaded to the ATmega328P using the Arduino IDE.

---

## Notes

- Ensure the required libraries are installed before compiling the project.
- Verify the I²C connections between the ATmega328P and MPU6050 before uploading the firmware.
- Calibrate the MPU6050 sensor before testing to achieve accurate posture detection.
