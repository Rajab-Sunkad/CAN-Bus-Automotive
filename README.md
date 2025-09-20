# CAN-Bus-Automotive
This project demonstrates CAN (Controller Area Network) communication using a PIC18F4580 microcontroller.   It simulates ECU (Electronic Control Unit) communication in automotive systems.

## Features
- CAN protocol implementation
- ADC integration
- Modular code with header and source separation
- Makefile-based build system

## Repository Structure
- `src/` → C source files
- `include/` → Header files
- `Makefile` → Build configuration
- `build/` → Compiler outputs (ignored in Git)

## Requirements
- MPLAB X IDE / XC8 Compiler
- PIC18F4580 Development Board
- CAN transceiver (e.g., MCP2551)

## Reference
Based on [Emertxe CAN Node for Automotive](https://www.emertxe.com/embedded-systems/micro-controllers/mc-projects/can-node-for-automotive/)

## How to Build
```bash
make
