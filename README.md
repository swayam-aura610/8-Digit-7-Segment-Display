# 8-Digit-7-Segment-Display
 Interface an 8-digit 7-segment LED display with 8 keys using an 8051 microcontroller to demonstrate multimode message display.

## Overview  
This project demonstrates interfacing an 8-digit 7-segment LED display with 8 keys using the 8051 microcontroller (AT89C51). The system displays messages in 8 distinct modes, controlled by key presses, showcasing versatile message display patterns.  

## Features  
- **Key-Controlled Modes**:  
  - Key 1: Steady message  
  - Key 2: Blinking message  
  - Key 3: Rolling through right  
  - Key 4: Rolling through left  
  - Key 5: Even-numbered LEDs blinking, others steady  
  - Key 6: Odd-numbered LEDs blinking, others steady  
  - Key 7: Rolling message from outside to inside  
  - Key 8: Rolling message from inside to outside  

- Efficiently integrates hardware and software for dynamic message displays. 

## Tools Used  
- **Microcontroller**: AT89C51  
- **Software**:  
  - Keil uVision3 (programming)  
  - Proteus (simulation)  

## Components  
- 8051 microcontroller (AT89C51)  
- 8-digit 7-segment LED display  
- Transistors, resistors, capacitors, diodes  
- Crystal oscillator (12 MHz)  
- Push buttons  

## Applications  
- Digital clocks for displaying time  
- Commercial signboards for static or dynamic messages  
- Long and continuous message displays in public spaces  

## Circuit and Connections  
- **Port 0**: Connected to LED segments via 330Ω resistors.  
- **Port 2**: Drives the 7-segment LEDs using PNP transistors.  
- **Port 1**: Receives input from 8 keys in pull-down configuration.  
- Crystal oscillator connected to XTAL1 and XTAL2 for clock generation.  

![Proteus Diagram] ![interface led proteus diagram](https://github.com/user-attachments/assets/bde1785e-93da-486e-9eb6-dedee57cac16)


![Image]![WhatsApp Image 2025-01-05 at 18 56 23_316dd619](https://github.com/user-attachments/assets/d31d700d-2314-489a-9fce-414b52e4f19b)

![Demonstration of project]https://github.com/user-attachments/assets/91ea76b6-f05a-44a3-87a3-866e3427f844



) 

