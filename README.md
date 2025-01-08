Sound-Activated Robot

This repository contains the code and instructions for building a sound-activated robot using the ESP32 microcontroller. The robot responds to sound inputs, such as claps, to perform specific actions, such as moving forward, backward, turning, or stopping.

Features

Detects sound using a sound sensor or microphone module.
Responds to different sound patterns (e.g., one clap, two claps) with pre-programmed actions.
Uses the ESP32 microcontroller for processing and control.
Easily customizable and extendable for additional features.

Components Required
Hardware:

ESP32 microcontroller
Sound sensor 
Motor driver 
DC motors and wheels
Chassis for the robot
Power supply (battery pack compatible with ESP32 and motors)
Jumper wires and connectors

Software:

Arduino IDE (with ESP32 board support installed)
Required libraries (detailed below)

How It Works

Sound Detection:
The sound sensor detects sound intensity.
The ESP32 interprets the sound patterns based on predefined thresholds and timing.

Action Execution:
Depending on the detected pattern, the robot executes corresponding actions, such as moving forward, turning, or stopping.
