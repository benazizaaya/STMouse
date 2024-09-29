# STMouse
STMouse is an STM32-based mouse that uses the internal accelerometer of the STM32F407VG microcontroller for motion detection and utilizes the board's internal buttons to handle left-click, right-click, and middle-click functionality. This project leverages the ARM Cortex-M4 core and the integrated LIS3DSH accelerometer to track movement, while the built-in buttons provide essential mouse inputs, making the design both compact and efficient.

The mouse communicates with a computer via the USB HID interface, ensuring plug-and-play usability. This project highlights the versatility of the STM32 microcontroller and its internal components for building functional input devices with minimal external hardware.  

## Requirements

### Hardware

- **STM32F407VG Discovery** board (includes LIS3DSH accelerometer and onboard buttons).
- **USB cable** to connect to the computer.

### Software

- **STM32CubeIDE** (or compatible IDE such as Keil or IAR).


## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/STMouse.git

### 2. Open and Configure the Project
Launch STM32CubeIDE and import the project.

### 3. Build and Flash
Compile the project within STM32CubeIDE.
Flash the firmware onto your STM32F407VG Discovery board.

### 4. Connect and Use
Connect the STM32F407VG board to your computer via USB.
The device will be recognized as a USB HID mouse.
Wait until the calibration process is complete before using the mouse. The completion will be indicated by an LED.
Move the STM32F407VG board to control the cursor using its accelerometer.
Use the onboard buttons for left-click, right-click, and middle-click.


############### Editor : BenazizaAya ############
