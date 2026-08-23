# STM32F030C8T6 Custom Development Board

Custom-designed embedded development board built around the STM32F030C8Tx 
(ARM Cortex-M0), engineered from schematic to PCB layout as part of a 
Product Development Project at Saveetha School of Engineering.

## Overview

A compact, battery-powered embedded platform designed for firmware 
development, sensor integration, and data logging. The PCB was designed 
to align with LionCircuits' fabrication capabilities, ensuring 
manufacturability without compromising on design complexity.

## Key Features

- **MCU:** STM32F030C8Tx (ARM Cortex-M0)
- **Power Input:** USB Type-C for board power, UART programming, and 
  serial communication
- **Onboard Charging:** Integrated Li-Ion battery charging circuit with 
  direct battery support
- **Power Management:** Automatic USB/battery power path switching
- **Debug/Programming:** SWD interface, compatible with ST-LINK and 
  STM32CubeIDE
- **Regulation:** High-efficiency 3.3V DC-DC buck converter
- **Memory:** AT24C128 EEPROM over I²C
- **Storage:** MicroSD card interface (SPI) for sensor data logging
- **Expansion:** GPIO headers for external sensor integration
- **PCB:** Custom 2-layer board designed in KiCad

## Design Files

- `/schematic` — Schematic design files (KiCad)
- `/pcb` — PCB layout/routing files (KiCad)
- `/bom` — Manually curated BOM with component availability verified 
  against supplier stock before finalization
- `/docs` — Design notes and power architecture

## Skills Demonstrated

Embedded Hardware Design · Schematic & PCB Design · Power Path & Battery 
Charging Circuit Design · DC-DC Converter Design · USB Type-C Integration · 
SWD, UART, SPI & I²C Interfacing · Component Sourcing & BOM Management · 
Design for Manufacturing (DFM)

## Background

Designed and presented as part of the Product Development Project, 
B.E. Electronics and Communication Engineering, Saveetha School of 
Engineering, Chennai. Also presented at the Big Star Summit.
