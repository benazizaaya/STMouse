# mouse_stm32f407

## Overview

This project implements a mouse interface using the built-in accelerometer of the STM32F407 microcontroller.
The microcontroller reads motion data from its integrated accelerometer and provides a USB interface for computer interaction,
 simulating a mouse.

##Hardware Requirements

To build this project, you will need:
STM32F407 board
usb to mini usb cable

##Software Requirements 

To program the STM32F407 board, you will need a toolchain that supports ARM Cortex-M processors.
 We recommend using the STM32CubeIDE, which is a free integrated development environment (IDE) provided by STMicroelectronics.

##Usage
Clone this repository to your local machine.
Open the project in STM32CubeIDE.
Build the project and flash it to the STM32F407 board.
Connect the USB cable  to the STM32F407 board and to the pc .

##Configuration
To configure the mouse, press and hold the designated button, then wait for the LED to indicate completion.