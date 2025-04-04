# **Smart Thermostat Prototype**  
*Embedded C, TI Development Board*

## **Overview**
The **Smart Thermostat Prototype** is an embedded system designed to manage temperature sensing and control using a variety of protocols including **I2C**, **GPIO**, and **UART**. This thermostat adjusts room temperature and provides feedback using LEDs to indicate system status. Task scheduling is integrated to optimize temperature adjustments based on real-time sensor data.

Developed as part of the **Embedded Systems** course at Southern New Hampshire University, this project demonstrates my ability to work with low-level embedded programming and hardware interfaces.

## Features
- **Temperature Sensing**: Collect real-time temperature data using sensors interfaced via I2C.
- **Device Control**: Control heating or cooling devices based on temperature thresholds.
- **LED Feedback**: LED indicators provide system status feedback, such as active heating or cooling.
- **Task Scheduling**: Efficient task management to adjust the temperature based on user-defined conditions.

## Technologies Used
- **Embedded C**: The programming language used for system development.
- **TI Development Board**: The hardware platform used for the project.
- **I2C**: Protocol used for communication with temperature sensors.
- **GPIO**: General-purpose input/output pins used to control devices like LEDs and relays.
- **UART**: Protocol used for serial communication for system feedback or debugging.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Smart-Thermostat-Prototype.git
2. Open the project in Code Composer 10.1.1.
3. Build the code onto the TI Development Board.
4. Monitor and adjust the thermostat settings using the buttons and LED feedback.
