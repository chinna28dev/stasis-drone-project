<img width="4032" height="2268" alt="1_R4VRDgKRKOV6ZHccD0GWzA" src="https://github.com/user-attachments/assets/c358b01c-fc87-4c09-85c5-d8008ca918a7" />

Reference image

# stasis-drone-project

#open source diy Educational drone 
### custom drone build from scratch with self-made transmitter,receiver& Flight controller

##project overview 
This project is focused on building a quadcopter drone completely from scracth using custom-designed electronics and open-source software.
Instead of using prebuilt commercial flight controllers and radio systems,this project aims to design and develop:
-custom handheld transmitter
-custom on board receiver
-custom flight controller
-drone frame and hardware integration
-stabilization firmware
-oopen-source documentation for learning

this goal is to learn and demonstrate real- world skills in:
-embedded systems 
-RF communucation
-sensor fusion
-flight stabilization
-mechanical design 
-electronics prototyping
open source hardware development


--
## Project Goals

### Main Goal
Create a working educational drone platform built using self-designed systems.

### Sub Goals

- Build custom transmitter using joystick controls
- Build custom receiver for drone communication
- Read IMU sensor data for balance and movement
- Implement PID stabilization
- Control 4 motors safely
- Design modular drone frame
- Document everything publicly on GitHub

---

## Features Planned

- 2.4GHz wireless control system
- Real-time joystick input
- Gyroscope + accelerometer stabilization
- Arming / disarming safety logic
- Battery monitoring
- Failsafe on signal loss
- Expandable GPS support
- Open-source firmware updates

---

## Hardware Stack

### Transmitter

- ESP32 Dev Board
- 2x Joystick Modules
- NRF24L01 RF Module
- OLED Display (optional)
- 18650 Battery Pack
- Power Switch
- Custom Case

### Drone Receiver + Flight Controller

- ESP32 / STM32
- NRF24L01 RF Module
- MPU6050 IMU Sensor
- Power Distribution Board
- ESC x4
- Brushless Motors x4
- LiPo Battery
- Propellers
- Drone Frame

---

## Software Stack

- Arduino IDE / PlatformIO
- C++
- PID Control Logic
- RF Communication Protocol
- Sensor Filtering
- GitHub for version control

---

