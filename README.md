# PLC-Tank-Control-System-Siemens-S7-1500

## Description
This project implements a tank level control system using Siemens S7-1500 PLC.

The system controls two tanks, pumps, and a mixer, ensuring safe and stable operation with multiple protection mechanisms.

## Features
- Control of two-tank system
- Pump and mixer automation
- Emergency stop handling
- Overtemperature protection
- Overflow and dry-run prevention
- Alarm system for fault conditions

## Technologies Used
- Siemens S7-1500
- TIA Portal
- PLCSIM

## System Logic
- Pump1 transfers liquid between tanks
- Pump2 activates during overheating
- Mixer operates when conditions are safe
- Fault conditions stop the system immediately

## Safety Features
- Emergency stop
- Overtemperature protection
- Overflow prevention
- Dry-run protection

## Simulation
The system was tested using Siemens PLCSIM with multiple scenarios:
- Normal operation
- Overflow condition
- Fault and emergency stop

## Project Goal
The goal of this project was to design and implement an industrial-style PLC control system with safety and fault handling.
