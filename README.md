# DHT11-temp-and-humidity
This repository contains code to read and display humidity and temperature data from a DHT11 sensor using an ESP32 microcontroller. The code also calculates the heat index, providing a measure of how hot it feels when humidity is factored in with the actual air temperature.

Table of Contents
Overview
Features
Hardware Requirements
Pin Configuration
Installation
Usage

This project demonstrates how to interface a DHT11 temperature and humidity sensor with an ESP32 microcontroller. The sensor readings are printed to the Serial Monitor, and the heat index is computed to give a sense of how hot it feels considering the humidity.

Features
Humidity and Temperature Reading: Reads data from the DHT11 sensor.
Heat Index Calculation: Computes the heat index in both Fahrenheit and Celsius.
Serial Monitoring: Outputs the sensor readings to the Serial Monitor.
Hardware Requirements
ESP32 Wroom 32D Development Board
DHT11 Temperature and Humidity Sensor
Connecting wires
Pin Configuration
ESP32 Pin	Description
18	DHT11 Data
Installation


Install the DHT sensor library from the Library Manager:

Go to Sketch > Include Library > Manage Libraries.
Search for DHT sensor library and install it.
Connect your ESP32 to your computer.

Select the appropriate board and port in the Arduino IDE.

Upload the code to your ESP32.

Usage
Connect the DHT11 sensor to the ESP32 according to the pin configuration table.

Power up the ESP32.

Open the Serial Monitor in the Arduino IDE with a baud rate of 115200.

The Serial Monitor will display the humidity, temperature in Celsius, and heat index.
