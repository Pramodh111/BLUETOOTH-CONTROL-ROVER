
# Bluetooth Controlled Rover Using Arduino

## Project Overview
The **Bluetooth Controlled Rover** is an embedded systems project that allows a user to control a robotic vehicle wirelessly using a smartphone. The rover receives commands through Bluetooth and moves in the required direction using a motor driver and DC motors.

## Objectives
- To design and develop a Bluetooth-controlled robotic rover.
- To establish wireless communication between a smartphone and Arduino.
- To control the movement of the rover using mobile commands.
- To understand embedded systems, motor control, and Bluetooth communication.

## Components Required
- Arduino Uno
- Bluetooth module (HC-05 or HC-06)
- Motor driver module (L298N or equivalent)
- DC geared motors
- Robot chassis and wheels
- Battery
- Connecting wires
- Android smartphone

*Update this list according to the components used in your project.*

## Working Principle
1. The smartphone connects to the rover through Bluetooth.
2. The user sends movement commands using a mobile application.
3. The Bluetooth module receives the commands and sends them to the Arduino.
4. The Arduino processes the commands and controls the motor driver.
5. The motors rotate in the required direction to move the rover.

## Movement Controls

| Command | Movement |
|---|---|
| F | Forward |
| B | Backward |
| L | Left |
| R | Right |
| S | Stop |

*These are example commands. Replace them if your code uses different commands.*

## Block Diagram

```text
 Smartphone
     |
  Bluetooth
     |
 Bluetooth Module
     |
   Arduino
     |
  Motor Driver
     |
   DC Motors
     |
    Rover
```

## Applications
- Wireless robotic vehicle control
- Embedded systems learning
- Robotics demonstrations
- Basic automation projects
- Educational and academic projects

## Skills and Technologies
- Arduino
- Embedded Systems
- Bluetooth Communication
- Motor Control
- Basic Robotics

## Repository Structure

```text
BLUETOOTH-CONTROL-ROVER/
│
├── README.md
├── Arduino_Code/
│   └── rover.ino
├── Images/
│   └── rover.jpg
└── Diagrams/
    └── block_diagram.png
```

*Add folders and files only when you have them.*

## Future Improvements
- Add obstacle detection using ultrasonic sensors.
- Add voice-based control.
- Add speed control using PWM.
- Integrate a camera for remote monitoring.

## Author
**Pramod K**  
B.Tech ECE Student  
Interested in Embedded Systems, Robotics, and VLSI.

## Note
This repository contains the project files and documentation. Hardware details, commands, and implementation information should match the actual project code and circuit.
