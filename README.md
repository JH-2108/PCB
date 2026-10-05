# Reaction game PCB

A compact physical reaction game built around a Raspberry Pi Pico and a custom-designed PCB 

# Overview

The Reaction Game challenges the player to react as quickly as possible when one of the LEDs lights up. the players must press the corresponding button, with the Raspberry Pi Pico controlling the LEDs, buttons, and buzzer. 

The goal is to turn a simple reaction game into a fully functional standalone PCB. 

# Features 
- 4 reaction LEDs
- 4 corresponding game buttons
- 1 start button
- Raspberry Pi Pico microcontroller
- Active buzzer for audio feedback (such as high scores and game over)
- Custom-designed PCB
- Multiple possible game modes and difficulty levels
- Compact physical design

# How it works 
1. The player starts the game using the Start button.
2. The Raspberry Pi Pico randomly selects and LED.
3. The selected LED lights up.
4. The player presses the corresponding button as quickly as possible.
5. The Pico measures the player's response and provides feedback through the LEDs and buzzer.
6. The game continues with increasingly challenging reactions.

# PCB Design
The PCB is designed in **KiCAD**. The schematic is created first, followed by component placement and PCB routing. 

The final PCB will contain all of the components required to operate the game as a compact standalone device. 

# Goal 
The final result will be a small, functional reaction game that demonstrates PCB design, embedded programming, electronics, and physical hardware development. 



