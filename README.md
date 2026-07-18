# Posture Corrector using ATmega328P and MPU6050

A wearable embedded system designed to monitor user posture in real time using the MPU6050 inertial measurement unit (IMU) and an ATmega328P microcontroller. The system detects prolonged poor posture and provides immediate feedback through an alert mechanism, encouraging users to maintain proper posture during daily activities.

This project was developed using a custom-designed PCB, demonstrating practical skills in embedded systems, PCB design, sensor interfacing, and hardware implementation.

---

## Features

- Real-time posture monitoring
- Slouch detection using MPU6050 IMU
- ATmega328P-based embedded system
- Custom PCB design
- Immediate posture correction alert
- Compact, wearable design
- Low-cost implementation

---

## Hardware Components

| Component | Description |
|-----------|-------------|
| ATmega328P | Main microcontroller |
| MPU6050 | 3-axis Accelerometer & Gyroscope |
| Buzzer / Vibration Motor | User alert mechanism |
| Voltage Regulator | Stable power supply |
| Battery | Portable power source |
| Custom PCB | Designed for compact implementation |

---

## Software Used

- Arduino IDE
- Embedded C
- I²C Communication Protocol
- MPU6050 Library

---

## Working Principle

1. The MPU6050 continuously measures the orientation of the user's upper body.
2. Sensor data is transmitted to the ATmega328P through I²C communication.
3. The microcontroller processes the orientation data and compares it with predefined posture thresholds.
4. If poor posture is maintained beyond the set duration, the system activates the alert mechanism.
5. The user corrects their posture, after which the system resumes monitoring.

---

## Repository Structure

```
Posture-Corrector/
│
├── README.md
├── docs/
├── hardware/
│   ├── Schematics/
│   ├── PCB/
│   ├── Gerbers/
│   └── BOM/
├── firmware/
├── images/
└── results/
```

---

## Project Images

Add images here after uploading them.

- Final Device
- Custom PCB
- Hardware Assembly
- Testing Setup
- Working Demonstration

---

## Results

- Successfully detects incorrect posture.
- Generates real-time alerts for prolonged slouching.
- Compact hardware implementation using a custom PCB.
- Suitable for wearable posture monitoring applications.

---

## Future Improvements

- Bluetooth connectivity
- Mobile application integration
- Rechargeable battery management
- Data logging
- Machine learning-based posture classification
- Miniaturized wearable enclosure

---

## Skills Demonstrated

- Embedded Systems
- PCB Design
- Sensor Interfacing
- ATmega328P Programming
- I²C Communication
- Hardware Debugging
- Wearable Electronics

---

## Authors

This project was developed by:

- Maria Rajiv
- Neha Savy
- Pavithra Mohan
- Surydev G
  
B.Tech Electronics and Communication Engineering

Mar Athanasius College of Engineering

---

## Acknowledgements

Special thanks to the project guide and team members for their support throughout the development of this project.
