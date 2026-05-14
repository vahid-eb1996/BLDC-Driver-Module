# BLDC Driver Module

Custom BLDC motor driver module designed for 12–48 V operation and up to 15 A target current.

## Overview

This project is a custom PCB design for a three-phase BLDC motor driver.  
It is based on an STM32G431 microcontroller, DRV8353 three-phase gate driver, external six-MOSFET power stage, current sensing, Hall sensor input, encoder input, USB-C interface, SWD programming, onboard logic power regulation, and input protection.

## Main Features

- 12–48 V input voltage range
- Up to 15 A target current
- STM32G431 MCU
- DRV8353 three-phase gate driver
- Six-MOSFET inverter power stage
- Current sensing
- Hall sensor interface
- Encoder interface
- USB-C interface
- SWD programming/debug connector
- Onboard 3.3 V logic supply
- Input fuse, TVS protection, and DC bus filtering

## Project Status

Prototype design completed.  
Manufacturing and validation are the next steps.

## Hardware Overview

The design includes the following main blocks:

- Power input and protection stage
- DC bus capacitors and filtering
- DRV8353 gate-driver stage
- Three-phase MOSFET inverter
- STM32G431 control stage
- Hall sensor and encoder feedback interfaces
- USB-C communication/programming interface
- SWD debug connector
- Expansion connector

## Next Validation Steps

- PCB fabrication and assembly
- Low-voltage bring-up
- Power-rail verification
- PWM and gate-signal measurement
- Current-sense calibration
- Hall/encoder input testing
- Motor-load testing
- Thermal validation at different current levels

## Notes

This project is currently in the prototype validation stage and is not yet a certified or production-ready motor controller.
