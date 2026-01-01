# Binary-Driven Seven-Segment Display Using Discrete Logic

# Overview
This project involved designing and building a seven-segment display system using discrete logic ICs. The circuit converts binary input states into the appropriate seven-segment outputs to display a fixed numerical sequence.

# Project Goal
The goal was to design a digital logic system using only AND, OR, and NOT gates, validate its behavior in simulation, and implement the design on physical hardware.

# System Overview
- Binary input logic designed using discrete logic gates
- Circuit simulated and verified in Multisim
- Physical implementation on a breadboard
- Output displayed on a seven-segment display

# Hardware Used
- AND, OR, NOT logic ICs
- Seven-segment display
- Breadboard and jumper wires
- Current-limiting resistors

# Software & Tools
- Multisim (logic simulation)

# Implementation Details
Each segment of the display was driven by Boolean expressions derived from the binary input states. The logic was first verified in Multisim before being transferred to a breadboard, where careful wire routing and step-by-step testing were required to ensure correct segment activation.

# Challenges & Debugging
Debugging involved identifying wiring errors and incorrect logic paths that caused unintended segment activation. These issues were resolved by isolating individual segment logic, verifying truth tables, and incrementally testing outputs.

# Results
- Successfully displayed the intended numerical sequence
- Correct operation verified in both simulation and hardware
- Stable and repeatable performance

# Future Improvements
Future improvements could include implementing the design on a PCB, reducing gate count through logic minimization, or using a microcontroller-based decoder for scalability.
