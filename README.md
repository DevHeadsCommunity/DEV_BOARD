# STM32 Cortex-M0 Development Board


## Project overview
Develop a low-cost development board featuring an STM32 Cortex-M0 microcontroller with integrated sensors, display, and debugging capabilities. 
The board will support USB debugging and UART communication, making it suitable for prototyping applications requiring motion sensing and environmental data collection.

## Key Features

1. Microcontroller: STM32F072C8T6 (Cortex-M0, USB Full-Speed 2.0)

2. Sensors:

i. LSM6DS3 (6-axis IMU: Gyroscope + Accelerometer)

ii. QMC5883L (Magnetometer)

iii. Temperature sensor

3. Display Options:

i. 1x 7-segment display or 4x LEDs (whichever is cheaper)

4. Onboard Debugging:

i. USB-to-UART via CH340T

5. Supports automatic bootloader mode via DTR/RTS

6. Expansion & Connectivity:

i. Multiple GPIOs for prototyping

ii. Space for additional headers

## Design and Development

The hardware design is being developed using KiCad, focusing on creating a compact and cost-effective PCB layout. 
This project does not include firmware development but provides a solid hardware platform for future software implementation.

## Components needed
1. STM32F072C8T6 Microcontroller: Core processing unit

2. LSM6DS3 + QMC5883L: Motion sensing and magnetometer

3. 7-segment display / LEDs: Visual output

4. CH340T USB-to-UART: Serial communication and flashing support

5. Supporting Components: Resistors, capacitors, headers, etc.

##   PCB Design Plan

1. Schematic Design

i. Connect STM32F072C8T6 with sensors, display, and USB debugging interface.

ii. Ensure power regulation and signal integrity.

2. PCB Layout

i. Optimize component placement for a compact and efficient design.

ii. Route signals carefully to minimize interference.

3. Prototype & Testing

i. Manufacture PCB and verify electrical connections.

ii. Validate power delivery and communication between components.
