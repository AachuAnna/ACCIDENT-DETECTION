# Accident Detection System 🚗🚨

An Arduino-based accident detection system using a tilt sensor to identify sudden impacts and trigger emergency alerts.

## Features
- Accident detection using tilt sensor
- Buzzer and LED alert
- False-alarm cancellation button
- Automatic alert after timeout
- Serial monitor status messages

## Components Used
- Arduino UNO
- Tilt Sensor (SW-200D)
- Push Button (Cancel)
- Buzzer
- LED
- Resistors
- Breadboard & Jumper wires

## Working Principle
The tilt sensor detects sudden orientation changes that indicate a possible accident.  
When detected, the system activates a buzzer and LED alert.  
The user can cancel the alert within 5 seconds if it is a false alarm.  
If not cancelled, an emergency alert is triggered (simulated via Serial Monitor).

## Simulation Note
Emergency alert is simulated using serial output.  
In real hardware, this can be extended with GSM/GPS modules.

## Author
Aachu Anna Sony

