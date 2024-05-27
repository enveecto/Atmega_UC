# ATmega328P-based Microcontroller

## Overview
This repository contains the design files, firmware, and documentation for a custom microcontroller based on the ATmega328P.

![image](board.png)


## Features
- ATmega328P microcontroller
- Operating voltage: 5V
- Clock speed: 16 MHz
- Digital I/O pins: 14 (6 can be used as PWM outputs)
- Analog input pins: 6
- UART, SPI, I2C communication protocols
- On-board reset button and LED

## Hardware
### Schematics
You can find them in the `hardware/schematics` directory.

### PCB Layout
The PCB layout files are also provided in the `hardware/pcb` directory. Gerber files are included for manufacturing.

### Bill of Materials (BOM)
A detailed list of components required for this project can be found in `hardware/BOM.md`.

## Firmware
### Bootloader
This project uses the [Optiboot bootloader](https://github.com/Optiboot/optiboot) for the ATmega328P. 

## Getting Started
### Prerequisites
- [Arduino IDE](https://www.arduino.cc/en/software) or [AVR-GCC](https://gcc.gnu.org/wiki/avr-gcc)
- [AVRDUDE](http://www.nongnu.org/avrdude/)

### Instruction
You will need a USB to TTL convertor to Upload your firmware this does not comes with a builtin.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/enveecto/Atmega_UC.git
   cd Atmega_UC
