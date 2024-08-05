# Air-Monitoring-System
Overview
The Air pollution Monitoring IoT-based system designed to monitor pollution levels using solar power. This project integrates various sensors to provide real-time data on air quality, noise levels, temperature, and humidity. The system employs a power-efficient design with a 30% duty cycle to maximize the usage of harvested solar energy.

Features
Real-Time Monitoring: Continuous monitoring of environmental parameters including air quality (PM2.5 and PM10),MQ2 , MQ8 , MQ9 Gas sensors,  noise levels, temperature, and humidity.
Energy Efficiency: Utilizes solar panels and a battery system with a 30% duty cycle and relay module to optimize energy consumption.
Data Analysis: Provides frequency analysis and power spectral density (PSD) plots for detailed insights into environmental data.
Connectivity: Integrated with Arduino Mega and ESP8266 modules for seamless sensor integration and Wi-Fi connectivity.
System Components
Solar Panels: Harvest solar energy to power the system.
Battery and Solar Charge Controller: Store and manage power supply for continuous operation.
Arduino Mega and ESP8266 Modules: Control and communication for sensor data collection and transmission.
Sensors:
Gas Sensors ( MQ2 , MQ8 , MQ9 )
Air Quality Sensors (PM2.5 and PM10)
Noise Level Sensor
Temperature and Humidity Sensors
Relay Module: Implements a 30% duty cycle to manage power consumption.
Installation
Hardware Setup:

Connect the solar panels to the solar charge controller and battery.
Connect the Arduino Mega and ESP8266 modules to the sensors and relay module as per the circuit diagram.
Ensure all components are securely connected and powered.
Software Setup:

Clone this repository to your local machine:
bash
Open the Arduino IDE and load the provided code files for the Arduino Mega and ESP8266 modules.
Upload the code to the respective microcontrollers.
Configuration:

Update the Wi-Fi credentials and other configuration parameters in the code.
Ensure the sensors are calibrated and the relay timings are set as per the 30% duty cycle requirements.
Usage
Once the system is powered and configured, it will start collecting and transmitting real-time data.
Access the data through the specified endpoint or interface to monitor pollution levels and other environmental parameters.
Use the frequency analysis and PSD plots for detailed insights into the collected data.
Contribution

