# Smart-Thermostat-Prototype

## Description
This project is a prototype for a smart thermostat developed using Embedded C and a Texas Instruments (TI) Development Board. It features I2C-based temperature sensing, GPIO input for adjusting settings, and UART communication to simulate data transmission to a server. The system uses LED feedback to indicate heating status based on user input.

## Features
- **Temperature Sensing**: I2C sensor for reading temperature values.
- **User Input**: Adjust settings via GPIO buttons.
- **Data Communication**: UART used to simulate communication with a server.
- **LED Feedback**: Visual indicator for system status (e.g., heating on/off).

## Technologies Used
- Embedded C
- Texas Instruments CS3220x-LAUNCHXL Development Board
- I2C, GPIO, UART

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Smart-Thermostat-Prototype.git
2. Open the project in Code Composer 10.1.1.
3. Build the code onto the TI Development Board.
4. Monitor and adjust the thermostat settings using the buttons and LED feedback.
