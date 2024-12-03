Smart Home System - C++ Console Application

This Smart Home System is a console-based application implemented in C++ that allows users to manage a collection of smart devices using an object-oriented approach. The system supports various smart devices, including lights, thermostats, temperature & humidity sensors, speakers, sockets, and radiator valves, allowing users to control and interact with them .

Key Features
Device Management: Add, interact with, and control a variety of devices such as:
Light: On/Off, Adjust brightness, Sleep timer.
Temperature & Humidity Sensor: Live and historical data.
Speaker: Adjust volume, Play/Stop.
Heating Thermostat: On/Off, Schedule, Heating boost (1 hour).
Socket/Plug: On/Off, Schedule, Sleep timer.
Radiator Valve: On/Off, Current temperature, Schedule.
Quick View: Displays device status at a glance. Example for a Light:
Bedroom: 60% Brightness [switch off]
Bedroom: off [switch on]
Sorting: Devices can be sorted by name or device type with secondary sorting by name.
Interactive Control: Interact with any device's full feature set through an intuitive, menu-driven interface.
Persistent Data Storage: The system loads and saves device data to/from a single file at the start and end of the session.
Menu System
Upon startup, the following options are available:

[device name]: Perform that device’s one-click action
1: List devices
2: Sort by name
3: Sort by device type (by name as secondary order)
4 [device name]: Select device to interact with its full feature set
5: Add device
9: Exit
Device Interaction
Each device supports specific actions such as:

Light: Toggle on/off, adjust brightness, set sleep timer.
Temperature & Humidity Sensor: View current readings.
Speaker: Control volume and playback.
Thermostat: Adjust on/off, set schedule,set tempreture .
Socket/Plug: Toggle power, set schedule.
Radiator Valve: Control on/off, adjust temperature, set schedule.
File Management
At the beginning of the program, the system loads all devices from a file into memory.
Upon exiting, the system saves the current state of all devices back to the file to persist changes.
Robust User Input
The application is designed to handle various user inputs gracefully, ensuring a smooth experience while interacting with the devices.
Use Cases
Educational Tool: Ideal for learning and practicing C++ with object-oriented principles such as inheritance, polymorphism, and dynamic memory management.
Smart Home Applications: This project can serve as a foundation for more complex IoT-based smart home systems.
