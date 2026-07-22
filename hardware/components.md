# Hardware Components

This document lists the primary hardware components used in the Arduino-based RC robotic system.

## Component List

| Component | Quantity | Purpose |
|---|---:|---|
| Arduino Uno | 1 | Main microcontroller responsible for processing control commands and controlling robot movement |
| L298D Motor Driver | 1 | H-Bridge motor driver used to control the direction of the DC motors |
| Low-RPM DC Motors | 2 | Provides mechanical drive and movement to the robot |
| HC-05 Bluetooth Module | 1 | Enables wireless communication between the robot and the remote/mobile controller |
| 2200 mAh LiPo Battery | 1 | Provides electrical power to the robotic system |
| Jumper Wires | As required | Used for electrical connections between the Arduino, motor driver, Bluetooth module, and other components |

## Main Controller

### Arduino Uno

The Arduino Uno serves as the central controller of the robot.

Its primary responsibilities include:

- Receiving Bluetooth control commands
- Processing directional instructions
- Controlling motor direction
- Executing forward, backward, left, right, and stop movements

## Wireless Communication

### HC-05 Bluetooth Module

The HC-05 Bluetooth module provides wireless communication between the robot and the controlling device.

The control system receives directional commands through Bluetooth and sends them to the Arduino for real-time execution.

## Motor Control

### L293D Motor Driver

The motor driver acts as the interface between the Arduino and the DC motors.

It allows the controller to:

- Change motor direction
- Execute forward and backward motion
- Perform left and right turns
- Stop the drivetrain

## Power System

A 2200 mAh LiPo battery is used as the primary power source for the robotic system.

The battery provides the required power for the control electronics and motor-drive system.

---

> Note: Hardware configurations may vary between RoboSoccer, Roborumble, and Deathrace implementations depending on competition requirements.
