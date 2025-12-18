# Ladder Project – Leather Feeding Screws for Leather Cutter

## Overview
This project consists of Ladder programming (ISPSoft) for a system that controls two leather feeding screws used in a leather cutter at a collagen processing industry.  
The system was designed to ensure safe, independent, and reliable operation of each screw, including logical interlocks and emergency stop functionality.

## Project Objectives
- Independently control two leather feeding screws  
- Allow local/remote operation via pulse buttons  
- Prevent reversal of rotation during startup or operation  
- Ensure immediate stop in emergency situations  
- Follow best practices in industrial automation safety  

## Functional Description

### System Logic
- The system has a start/stop pulse button  
- The system operates only when the start is active  
- Pressing the start button again turns the entire system off  
- An emergency stop button immediately disables all outputs  

### Screw Control (Screw 1 and Screw 2)
Each screw operates fully independently:  
- Two pulse buttons:  
  - Clockwise rotation  
  - Counterclockwise rotation  
- Operation:  
  - Press once → screw rotates in the selected direction  
  - Press again → screw stops  
- Logical interlock:  
  - Opposite rotation cannot be activated while the screw is moving  
  - To reverse direction, the screw must first stop  

### Safety
- Emergency stop has top priority  
- Interlock between rotation directions  
- Activation is blocked if the system is not enabled (start off)  
- Prevents mechanical stress and operational risks during startup  

## Tools & Technologies
- **Software:** ISPSoft  
- **Programming Language:** Ladder  
- **Application:** Industrial Automation  
- **Environment:** Leather/collagen processing industry  

## Project Status
- Ladder programming completed  
- Logic tested in development environment  
- Project ready for practical application and field commissioning  

## Author
Gabriel Oliveira dos Santos  
Bachelor in Electrical Engineering (in progress)  
Technician in Electromechanics and Electro-electronics

