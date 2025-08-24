# Smart Home Automation integrated with Web Interface and ESP8266 Module

## Table of Contents

- [Description](#description)
- [Components Used](#components-used)
- [Installation](#installation)
- [Contributing](#contributing)

## Description

The Smart Home Automation project is designed to create an efficient, user-friendly, and cost-effective system for controlling and monitoring various home appliances and environmental parameters. By integrating a web interface and ESP8266 module, users can remotely access and control their home devices, ensuring convenience and energy conservation.

## Components Used

- Arduino Uno: A microcontroller board based on the ATmega328P, used as the central processing unit for the system.
- ESP8266: A low-cost Wi-Fi module that enables wireless communication and remote access to the system.
- 4 Channel Relay Module: An interface that allows the Arduino to control high-voltage appliances safely.
- Water Level Sensor: A sensor that detects the water level in a container, providing feedback for water management.
- Magnetic Reed Switch: A switch that detects the opening and closing of doors or windows, enhancing home security.
- DHT11 Temperature/Humidity Sensor: A sensor that measures ambient temperature and humidity, providing data for climate control.

## Installation

To set up the system, follow these steps:

1. Install Python 3 and the Pyngrok library by running `pip install pyngrok`.
2. Install Node.js and NPM (Node Package Manager).
3. Clone the repository to your local machine.
4. Navigate to the backend directory and run `npm install` to install the required dependencies.
5. Run `npm i`in the web interface directory.
6. In a new terminal window, navigate to the frontend directory and run `npm install` to install the required dependencies.
7. Run `python start.py` to start the frontend server.
8. Open the Arduino IDE and upload the Arduino sketch file to your Arduino Uno board.
9. Connect the Arduino Uno board to the 4 Channel Relay Module, Water level sensor, magnetic reed switch, and DHT11 temperature/humidity sensor based on the wiring diagram provided in the Arduino sketch file.

## Contributing

Contributions are welcome! Please create a pull request to contribute to this project.
