IoT Project: Temperature Detection and Control System
This project explores the implementation and application of IoT technology through five structured assignments and a personal design project. The focus is on using microcontrollers and IoT protocols to develop a temperature detection alarm system, capable of real-time monitoring and automatic alerts. The project also delves into IoT system architecture, communication protocols, and practical IoT applications.

Project Overview


Objective:

Develop a temperature detection system that reads ambient temperature, displays real-time data on an LCD, and triggers alarms (sound and LED) when thresholds are exceeded.
Explore IoT protocols and microcontroller applications in various exercises to demonstrate IoT's versatility.


Key Features:

Temperature Alarm System: Combines sensors and Zigbee communication for alerts and data logging.
IoT Protocol Exploration: Experiments with protocols like MQTT, CoAP, and custom solutions.
Custom Game Design: Demonstrates microcontroller versatility through joystick-controlled games.
Industrial IoT Applications: Proposes future developments for smart manufacturing.

Key Experiments

EX1: Basic control of LEDs and delays using microcontroller programming.
EX2: Interrupt handling and efficient use of system resources.
EX3: PWM control and LCD screen interaction for data visualization.
EX4: SPI communication between devices, simulating multi-device IoT interactions.
EX5: Ethernet-based data transmission for IoT applications.

Personal Design: Temperature Detection Alarm System

Description: A temperature sensor monitors ambient conditions and triggers alarms (Zigbee alerts and LED flashing) when a threshold is exceeded.
Applications:
Industrial IoT: Real-time monitoring and automatic cooling system activation.

Smart Homes: Remote temperature monitoring and control via IoT.

Healthcare: Ensuring temperature-sensitive environments like storage rooms or hospitals.

Tools and Technologies

Microcontroller: ARM Cortex-M-based microcontrollers (e.g., NXP K64F).

Communication Protocols: MQTT, CoAP, Zigbee.

Programming Environment: Mbed OS.

Sensors: Temperature sensors for real-time monitoring.

LCD: Real-time data visualization.

Future Developments

Automation: Integration with cooling/heating systems for automated temperature regulation.

Industrial Applications: Enhancing IoT solutions for environments with high thermal radiation, weak signals, or power constraints.

Sustainability: Optimizing energy consumption in IoT devices and networks.


How to Run

Clone the repository:

bash

Copy code

"git clone https://github.com/Baqiang11/IOT"

Flash the provided code to the microcontroller using Mbed OS.

Set up the sensors and communication modules as described in the documentation.

Run the system and monitor outputs on the LCD screen.
