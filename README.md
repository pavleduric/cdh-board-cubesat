# 🛰️ APEx CubeSat Mission: Command and Data Handling (CDH) Central PCB

## 📌 Project Overview
This repository showcases the hardware architecture and PCB design of the central Command and Data Handling (CDH) board developed for the APEx CubeSat mission. The CDH board serves as the central processing unit of the satellite, managing data routing, power states, and high-reliability communication interfaces across all subsystems.

*Note: Due to competition confidentiality and intellectual property protections, raw manufacturing files (Gerbers) and exact component values are omitted. This repository serves as a visual and architectural showcase of the PCB design and hardware integration.*

## ⚙️ Core Hardware Design & PCB Architecture
My primary focus on this project was the design, routing, and physical verification of the central CDH printed circuit board:

### 🔌 PCB Design & Schematic Capture
* **System Integration:** Designed the multi-layer stackup to host the mission's central microcontroller, memory, and managing signal integrity across high-speed data lines.
* **Peripheral Bus Topology:** Integrated communication buses (I2C, SPI, UART) to establish clean, reliable data routing between the core processor and critical flight peripherals.
* **Debugging & Regulations:** Followed all UNP CubeSat Satellite Requirements. Added debugging points for I2C, UART, and SPI lines.

## 🎛️ Technical Competencies & Toolchain
* **PCB Design & EDA:** Schematic Capture, Component Selection, Multi-layer Routing
* **Protocols & Hardware Interfaces:** SPI, I2C, UART, GPS Modules, Microcontroller Peripherals

## 📂 Repository Structure
* `/hardware`: High-level PCB 3D renders, layer stackup concepts, and top-level schematics (sanitized).
* `/media`: Future photos of the physical prototype, bench testing setups, and oscilloscope waveforms from board bring-up.
* `/docs`: High-level system architecture block diagrams explaining the inter-board data routing.
