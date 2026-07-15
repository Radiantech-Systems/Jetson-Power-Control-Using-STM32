# Jetson-Power-Control-Using-STM32
# Jetson Power Control Using STM32

This project demonstrates how an **STM32H753ZI NUCLEO-144** board can be used as a power controller for an **NVIDIA Jetson** platform.

The STM32 is responsible for controlling the Jetson power-on sequence and monitoring the system, making it suitable for embedded and edge AI applications where reliable power management is required.

## Features

- Power control using STM32H753ZI
- GPIO-based Jetson power enable
- STM32 HAL-based firmware
- Developed using STM32CubeIDE
- Easy to modify and extend

## Hardware

- STM32H753ZI NUCLEO-144
- NVIDIA Jetson AGX Orin (or compatible Jetson board)
- USB Cable
- External Power Supply

## Software

- STM32CubeIDE
- STM32CubeMX
- STM32 HAL Library

## Project Structure

```
Core/
Drivers/
POWER_CONTROL_JETSON.ioc
STM32H753ZITX_FLASH.ld
STM32H753ZITX_RAM.ld
README.md
```

## Getting Started

1. Clone the repository.
2. Open the project in STM32CubeIDE.
3. Build the project.
4. Flash the firmware to the STM32H753ZI board.
5. Connect the STM32 to the Jetson power control interface and test the power sequence.

## Future Work

- Watchdog support
- UART communication with Jetson
- Heartbeat monitoring
- Automatic power recovery
- Fault detection and logging

## Author

**Harshavardhan Yanadi**

Embedded Systems | STM32 | NVIDIA Jetson | Linux | Yocto
