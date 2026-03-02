# Gas-Smoke-Detection-System
# Gas & Smoke Detection System (ESP32 + MQ-2)

## Project Overview
This project detects **gas leaks and smoke** using an **MQ-2 gas sensor**
interfaced with an **ESP32**.

The sensor continuously monitors air quality and displays
the gas concentration and status on the Serial Monitor.

## Components Required
- ESP32
- MQ-2 Gas Sensor
- Jumper Wires
- Breadboard

## Connections
 MQ-2 Pin---->ESP32 Pin
VCC---->5V 
GND---->GND
AO ---->GPIO 34

## Working Principle
1. MQ-2 sensor detects gas concentration
2. ESP32 reads analog value from sensor
3. Air quality is classified based on threshold values
4. Status is shown on Serial Monitor

## Concepts Used
- Analog sensor interfacing
- ADC reading on ESP32
- Conditional logic
- Serial communication

## How to Run
1. Connect MQ-2 sensor properly
2. Upload the code to ESP32
3. Open Serial Monitor (9600 baud)
4. Observe gas readings and status
 
##  Sample Output
Gas Sensor Value: 1350
Status: Methane / Natural Gas Detected

## learning Outcome
- Understand gas sensor working
- Learn threshold-based decision making
- Build safety-based embedded systems
- 
##  Author
Harsha G
