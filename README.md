# Battery Charging System Using DC-DC Buck Converter

## Overview

This project presents the design and simulation of a PWM-controlled DC-DC buck converter for battery charging using MATLAB/Simulink.

A Constant-Current Constant-Voltage (CC-CV) charging strategy is implemented using PI-based closed-loop control to regulate the charging current and battery voltage.

## Objectives

- Design a DC-DC buck converter for battery charging.
- Implement PWM-based switching control.
- Implement CC-CV charging methodology.
- Design PI-based closed-loop voltage and current regulation.
- Analyze battery voltage, charging current, ripple, and converter efficiency.

## Software and Tools

- MATLAB
- Simulink
- Simscape Electrical
- PI Controller
- PWM Generator
- DC-DC Buck Converter

## System Description

The system consists of a DC input source, buck converter, feedback control system, and battery.

The battery voltage and charging current are measured and fed back to the controller. The PI controller adjusts the control signal, which determines the PWM duty cycle of the converter switch.

## CC-CV Charging

### Constant Current (CC) Mode

During the initial charging stage, the controller maintains the battery charging current at a desired reference value.

### Constant Voltage (CV) Mode

When the battery voltage reaches the specified voltage limit, the controller maintains the battery voltage at the reference value while the charging current gradually decreases.

## Simulation Model

![Simulink Model](Images/Simulink_Model.png)

## Results

The system performance is evaluated using:

- Battery voltage
- Charging current
- Output voltage
- Voltage/current ripple
- Converter efficiency
- Transient response

## Key Features

- PWM-controlled buck converter
- Closed-loop PI control
- CC-CV battery charging
- Voltage and current feedback
- MATLAB/Simulink simulation

## Applications

- Battery charging systems
- Electric vehicles
- Renewable energy storage
- Portable electronic devices
- Power management systems

## Future Scope

- Hardware implementation
- Battery Management System (BMS) integration
- Temperature-based charging control
- Improved converter efficiency
- Solar-powered battery charging
