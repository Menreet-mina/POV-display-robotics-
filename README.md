# POV Display Robotics Project

## Overview
This project is a **Persistence of Vision (POV) display system** that creates the illusion of floating text by rapidly spinning a set of LEDs and controlling their timing. By switching the LEDs on and off at precise moments while the device rotates, the system displays readable characters in the air.

The project combines embedded programming, robotics, and electronics to demonstrate timing control, sensor integration, and visual persistence effects.

## Features
- Displays text using a rotating LED array
- Real-time LED control synchronized with rotation
- Uses a sensor to detect the rotation position
- Compact embedded design using Arduino Nano
- Custom timing algorithms for stable text rendering
- Low-cost electronic components

## Components Used
- Arduino Nano
- LEDs
- Rotation sensor
- Resistors
- Transistor / driver components
- Motor and rotating mechanism
- Battery / power supply
- Connecting wires and PCB/breadboard

## How It Works
The Arduino Nano controls the LEDs while the system rotates at high speed. A sensor detects the position of the rotating arm, allowing the microcontroller to determine when each LED should turn on or off.

The display is created by rapidly changing LED patterns as the device spins. Due to the persistence of human vision, the sequence of light patterns appears as stable floating text.

## Hardware Architecture
1. The motor rotates the LED module.
2. The sensor provides position feedback to the Arduino Nano.
3. The Arduino processes the timing information.
4. LEDs are controlled according to predefined character patterns.
5. The viewer perceives the generated text image.

## Software
The Arduino program is responsible for:
- Reading sensor input
- Synchronizing LED timing with rotation
- Storing character patterns
- Controlling LED output sequences

## Applications
- Rotating LED displays
- Decorative displays
- Embedded systems demonstrations
- Robotics and electronics learning projects

## Future Improvements
- Add wireless control using Bluetooth/Wi-Fi
- Support more characters and animations
- Improve display resolution
- Add rechargeable power management
- Create a mobile application for text updates

## Authors
[Your Name]

## License
This project is open-source and available for educational and development purposes.
