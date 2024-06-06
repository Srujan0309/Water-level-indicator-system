
# Water Level Indicator System using 8051 Microcontroller

## Description

This project involves the development of a Water Level Indicator System using the 8051 microcontroller. The system monitors and indicates the water level in a tank or reservoir using LEDs and switches. This embedded system project provides real-time indication of water levels, ensuring efficient management and preventing overflows or dry runs.

## Components Used

- **Microcontroller:** 8051
- **LEDs:** 4 LEDs connected to Port 2 (P2^0, P2^1, P2^2, P2^3)
- **Switches:** 4 switches connected to Port 1 (P1^0, P1^1, P1^2, P1^3)
- **Other Components:** Resistors, Breadboard, Connecting Wires, Power Supply

## Working Principle

The system operates by continuously monitoring the state of four switches, which represent different water levels. Based on the status of these switches, the corresponding LEDs are turned on or off to indicate the current water level.

### Initialization

- All LEDs are configured as output pins and initially turned off.
- All switches are configured as input pins.

### Monitoring and Control

- The system runs in an infinite loop, continuously checking the state of the switches.
- Depending on the combination of switch states, the corresponding LEDs are activated to represent the water level:
  - **All switches on:** All LEDs on, indicating a full tank.
  - **Switch 1 on, others off:** Only the first LED on, indicating a low water level.
  - **Switches 1 and 2 on, others off:** The first two LEDs on, indicating a moderate water level.
  - **Switches 1, 2, and 3 on, the last off:** The first three LEDs on, indicating a high water level.
  - **All switches off:** All LEDs off, indicating an empty tank.

## Outcome

The Water Level Indicator System effectively monitors and displays the water level through LEDs, providing a simple yet efficient solution for water management. This project enhances my skills in embedded systems and real-time monitoring applications, demonstrating my proficiency with microcontrollers and practical electronics.

## Demonstration

[Include any images or diagrams here]

## Usage

To use this project, load the code onto an 8051 microcontroller, connect the switches and LEDs as specified, and power the system. The LEDs will indicate the water level based on the switch states.

## Future Enhancements

- Add buzzer alarm for critical water levels.
- Implement an LCD display for precise water level measurement.
- Integrate with IoT for remote monitoring.

## Contact

For any inquiries or contributions, please reach out to [Your Email] or connect with me on [LinkedIn Profile].

---

### Hashtags

#EmbeddedSystems #Microcontroller #WaterManagement #8051 #Electronics #RealTimeMonitoring #EngineeringProjects #LEDIndicator #IoT #TechInnovation

---

