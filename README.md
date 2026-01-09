# Robot Writer

## Overview

Robot Writer is a software-focused project centred on developing embedded C code to control an existing writing robot. The scope of this project was purely software, with no involvement in mechanical design, electronics selection, or physical setup of the robot.

The work focused on writing low-level C code to translate high-level writing instructions into coordinated motion commands, enabling the robot to write text accurately using its pre-existing hardware.

---

## Key Features

* Automated writing and drawing using a standard pen
* 2‑axis motion system for precise planar movement
* Embedded control using a microcontroller
* Custom firmware for coordinated motor control
* Modular mechanical design suitable for rapid iteration and improvement

---

## Project Scope

This project focused exclusively on embedded software development in C. The mechanical design, electronics, and physical assembly of the robot were provided beforehand and were outside the scope of this work.

---

## Software Environment

* Embedded C development on an Arduino Mega (ATmega2560)
* Development using the Arduino toolchain with low-level C-style programming
* Communication with the robot via a provided RS232 serial interface
* Use of given serial and RS232 driver files for low-level communication
* Focus on application-layer logic built on top of supplied communication code

---

## Software & Control

* Application code written entirely in C for the Arduino Mega
* Built on top of provided RS232 and serial communication files
* Conversion of characters into coordinate-based motion commands
* Formatting and transmitting motion commands over the serial interface
* Sequencing and synchronisation of multi-axis movement
* Timing-aware command generation for smooth and repeatable writing

---

## Results

* Robot successfully writes legible characters using the provided hardware
* Software produces repeatable and predictable motion
* Demonstrates reliable low-level motor control implemented in C

---

## Skills Demonstrated

* Embedded programming in C
* Working with existing RS232 / serial communication code
* Application-layer control over serial interfaces
* Low-level motor control via command-based protocols
* Real-time and timing-critical code
* Debugging and testing on physical hardware

---

## Future Improvements

* More advanced motion profiling (acceleration and jerk control)
* Support for additional fonts or vector inputs
* Optimisation of timing for smoother curves
* Porting firmware to alternative microcontrollers

---

## Project Motivation

The goal of this project was to strengthen skills in embedded C programming and low-level control of electromechanical systems. It demonstrates the ability to work close to hardware, manage timing-sensitive logic, and produce reliable firmware for a real-world robotic system.

---

## Author

Callum O’Neill

More projects available at: [https://eillcon.github.io/](https://eillcon.github.io/)
