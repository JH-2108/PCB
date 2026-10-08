# Small devboard 

A custom RP2040-based development board designed from scratch in KiCAD as part of Hack Club Half Life. 

The DevBoard is a compact general-purpose development platform with native USB-C connectivity, external QSPI flash, 3.3V power regulation, GPIO breakout, onboard controls, and a status LED. The board is intended to be used for embedded programming, electronics experimentation, robotics, sensors, displays, and future hardware projects. 

# Features 
- Raspberry Pi RP2040 microcontroller
- Native USB-C connectivity
- External QSPI flash
- 12 MHz crystal oscillator
- 3.3V power regulation
- 2x20 GPIO breakout pins
- BOOTSEL and RESET buttons
- Onboard status LED
- SMD components
- Custom PCB designed in KiCAD

# Hardware 
The board is built around the RP2040 and follows the required circuity for its power, clock, USB, and external flash interfaces. 

# Main components
- RP2040 MCU
- W25Q128 QSPI flash
- 12 MHz crystal
- USB-C connector
- 3.3V LDO regulator
- Decoupling and filtering capacitors
- USB-C CC resistors
- GPIO headers
- RESET and BOOTSEL buttons
- Status LED

# Firmware
The devboard will be programmed using the Raspberry Pi Pico SDK and C/C++. 

The initial firmware will provide: 
- RP2040 boot and initialization
- USB connectivity
- GPIO testing
- Status LED control
- Board diagnostics
- USB serial communication

A diagnostic firmware can be used to verify that the assembled PCB is functioning correctly. 

# PC software
A small optional Python utility may be developed to communicated with the board over USB serial. 

This can be used to 
- Display board information
- Run hardware tests
- Control the onboard LED
- Test GPIO
- Monitor diagnostic output

# Design
The PCB and schematic are designed using KiCAD. 
Project files include: 
- Schematic
- PCB layout
- Component/footprint assignments
- BOM
- Manufacturing files

# Design process
1. select and verify components for pricing and whether it is within budget range
2. create the schematic
3. assign symbols and footprints
4. design the PCB layout
5. route the board
6. run electrical and design rule checks
7. generate gerber files
8. assemble the PCB
9. develop and test firmware
10. test the complete board

# Project goals
The main goal is to design and build a fully functioning custom development board rather than relying on an existing development board such as the Raspberry Pi Pico. 

The project combines: 
- PCB design
- embedded systems
- electronics
- Firmware development
- USB communication
- hardware testing
- software development

# project images

**Schematic** 

<img width="1102" height="763" alt="image" src="https://github.com/user-attachments/assets/41344106-1482-4054-a64a-e4b68676cb39" />


**PCB layout**

<img width="1158" height="772" alt="image" src="https://github.com/user-attachments/assets/a9b2e89d-6178-4e05-9b75-6f9022821803" />


**3d Render**

<img width="765" height="525" alt="image" src="https://github.com/user-attachments/assets/d68ac82f-3e98-4bc5-8330-ee1c570f046d" />


**Finished PCB**
a photo will be added here 
