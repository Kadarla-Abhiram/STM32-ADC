# STM32 ADC - Potentiometer Reading

## Overview
This project demonstrates how to use the Analog-to-Digital Converter (ADC) of an STM32 microcontroller to read analog voltage from a potentiometer.

## Hardware Used

- STM32F1 BLUEPILL
- Potentiometer (10kΩ)
- USB Cable
- STM32CubeIDE

## Software Used

- STM32CubeIDE
- STM32 HAL Library

## Features

- ADC initialization
- Single channel conversion
- 12-bit ADC resolution
- Polling mode
- UART printf (optional)

## Working

1. Rotate the potentiometer.
2. ADC reads the analog voltage.
3. Voltage is converted into a digital value.
4. ADC value is displayed in the debugger or UART terminal.

## ADC Formula

ADC Value = (Input Voltage / Reference Voltage) × 4095

Example:

Input Voltage = 1.65V

Reference = 3.3V

ADC Value = 2048


## Learning Outcomes

- GPIO Analog Mode
- ADC Peripheral Configuration
- Polling Method
- HAL ADC Functions
- Analog Signal Processing

## Future Improvements

- DMA Mode
- Continuous Conversion
- Multi-Channel ADC
- Sensor Interfacing

## Author

Abhiram Kadarla
