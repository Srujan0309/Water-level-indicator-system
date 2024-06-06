
Project Title: Water Level Indicator System using 8051 Microcontroller

Description:

In this project, I developed a Water Level Indicator System utilizing the 8051 microcontroller. The system aims to monitor and indicate the water level in a tank or reservoir using LEDs and switches. This embedded system project provides a real-time indication of water levels, ensuring efficient management and preventing overflows or dry runs.

Components Used:

Microcontroller: 8051
LEDs: 4 LEDs connected to Port 2 (P2^0, P2^1, P2^2, P2^3)
Switches: 4 switches connected to Port 1 (P1^0, P1^1, P1^2, P1^3)
Other components: Resistors, Breadboard, Connecting Wires, Power Supply

Working Principle:

The system operates by continuously monitoring the state of four switches, which represent different water levels. Based on the status of these switches, the corresponding LEDs are turned on or off to indicate the current water level. The code is structured as follows:

Initialization:

All LEDs are configured as output pins and initially turned off.
All switches are configured as input pins.

Monitoring and Control:

The system runs in an infinite loop, continuously checking the state of the switches.
Depending on the combination of switch states, the corresponding LEDs are activated to represent the water level:
All switches on: All LEDs on, indicating a full tank.
Switch 1 on, others off: Only the first LED on, indicating a low water level.
Switches 1 and 2 on, others off: The first two LEDs on, indicating a moderate water level.
Switches 1, 2, and 3 on, the last off: The first three LEDs on, indicating a high water level.
All switches off: All LEDs off, indicating an empty tank.
