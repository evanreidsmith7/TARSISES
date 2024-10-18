# TARSISES: TARS Inspired Space Embedded System

## Project Overview

This project aims to build a miniature, functional replica of **TARS**, the iconic robot from the movie *Interstellar*. The idea is to create a proof of concept Space Exploration System used to explore potential habital planets.The system is developed on an **STM32F4 Nucleo** microcontroller and uses **FreeRTOS** for real-time task management. The robot will feature movement control, obstacle detection, and sensor-based telemetry, inspired by the walking and functionality seen in the movie. Addionally, the recent launch of the Europa Clipper sparked the idea of a space exploration system that could be used to explore potential habital planets. Robots like TARS could be used to explore the surface of these planets and collect data before risking human life.

## Motivation

The goal is to create an **RTOS-based control system** to manage TARS’s motor control, autonomous movement, and system monitoring, all within an embedded environment.

Ultimately, the project will serve as a learning platform for embedded systems, real-time operating systems, and robotics, with a focus on modular design and system integration. I wish to improve my skills to become a better candidate for embedded software/systems engineering roles.

### Skills to Develop

- **RTOS Task Management:** Task scheduling, inter-task communication, and real-time operation.
- **C/C++ for Embedded Systems:** Low-level code for motor control, sensor integration, and system monitoring.
- **Peripherals and Communication:** I2C, SPI, and UART for interfacing with sensors, displays, and motor drivers.
- **Motor Control and PWM:** Precise control of motors for movement and rotation.
- **Sensor Integration:** Obstacle detection and system health monitoring.
- **System Integration and Debugging:** Hardware-software integration and debugging techniques.

## Credits

This project is inspired by the [Hackster.io project by Charlie Diaz](https://www.hackster.io/charlie_diaz/tars-robot-from-interstellar-3d-printed-robot-1e1f1f), which features a 3D-printed TARS replica with a Raspberry Pi. I give special thanks to Charlie for his detailed documentation and design inspiration.

## Features

- **Mobility System**
  - PWM-based Servo control for movement and rotation
  - rotating legs
  - torso shifting
- **Modular Interaction Modes**
  - Task scheduling using FreeRTOS
  - Different operation modes (Idle, Movement, Sampling, etc.)
- **Autonomous Navigation**
  - Obstacle detection using ultrasonic sensors
  - Basic navigation and obstacle avoidance
- **Telemetry**
  - UART-based telemetry system
  - Report data over monitor *(for now)*
- **Custom Enclosures:** 3D printed mechanical parts and enclosures inspired by the Hackster.io project by Charlie Diaz

## Hardware Components

- **STM32F4 Nucleo** (Main Microcontroller)
- **SG90 Micro Servo Motors** (x4)
- **Metal Gear Servos** (x5)
- **Adafruit 16-Channel PWM Servo Driver** (I2C)
- **display???**
- **Ultrasonic/IR Sensors** (for obstacle detection)
- **LiPo Battery (3S, 1300mAh)** with **DC-DC Buck Converter**
- **Lightweight Actobotics Servo Horn (H25T Spline)**
- **3D Printed Chassis and Enclosure** (files available in the repo)

## Software Components

- **FreeRTOS** for task management
- **STM32CubeMX** for peripheral configuration (PWM, I2C, UART)
- **PWM** for motor control (servo and DC motors)
- **I2C** for interfacing with the servo driver and sensors
- **UART** for telemetry data communication
- **CAD** software for designing custom 3D-printed parts

## Project Structure

```bash
RTOS-TARS-Control-System/
├── docs/                # Documentation, schematics, diagrams
└── README.md            # Project introduction and Status Tracking
└── CAD                  # CAD files
└── ...                  # tbt

```

## Project Status

- Prep
