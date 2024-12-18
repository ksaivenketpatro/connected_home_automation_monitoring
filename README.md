# Connected Home: Automation & Monitoring

## Overview
The **Connected Home: Automation & Monitoring** project integrates **IoT technologies** and **embedded systems** to monitor and control various home systems. The project aims to provide a seamless and efficient smart home solution, where multiple **room modules** equipped with various sensors (e.g., temperature, humidity) collect data and wirelessly communicate to a **central dashboard** located in the living room. This central dashboard displays real-time data from all rooms, as well as automated systems like the **aquarium** and **plant watering system**, which are controlled based on sensor inputs.

## Core Components
- **Room Modules**: Each room has sensors (temperature, humidity, etc.) to monitor environmental conditions. These room modules send sensor data to the central dashboard via **Wi-Fi**.
- **Central Dashboard**: The central physical display shows real-time data from all room modules, along with the automation status of systems like the aquarium and plant watering system. This dashboard is powered by **ESP32 microcontrollers** which handle the sensor data processing and automation tasks.
- **Automation Systems**: The system uses **ESP32** microcontrollers to control actuators like lights, pumps, or watering systems based on the sensor data.
- **Web App**: A **web application** allows users to monitor and control the system remotely. Real-time data from the room modules is transferred to the central dashboard and then pushed to the web app via protocols like **MQTT** or **HTTP**. The web app provides a user-friendly interface for visualizing data and controlling devices from anywhere.

## Features
- **Real-time Monitoring**: Display and monitor environmental data (temperature, humidity, etc.) from all rooms and connected systems (aquarium, plant watering).
- **Automation**: Automated control of devices such as lights, pumps, and watering systems based on sensor data.
- **Remote Access**: Control and monitor all systems remotely using a web app that provides live data and control features.
- **IoT Communication**: Communication between room modules, central dashboard, and the web app using **Wi-Fi**, **MQTT**, and **HTTP** protocols.

## Technologies Used
- **ESP32 Microcontroller**: Used for sensor data collection, processing, and communication between modules.
- **Sensors**: Includes temperature, humidity, soil moisture, and water temperature sensors.
- **Wi-Fi**: Wireless communication for data transfer between modules, dashboard, and web app.
- **RTOS**: Real-Time Operating System used on ESP32 for efficient task management and execution.
- **Web Technologies**: Front-end development using **HTML**, **CSS**, **JavaScript** for the web app.
- **Protocols**: **MQTT** or **HTTP** for real-time data synchronization between the central dashboard and web app.

## Learning Outcomes
- **Embedded Systems**: Learn to work with microcontrollers, sensor integration, and real-time task management.
- **IoT Communication**: Understand and implement wireless communication protocols like **Wi-Fi**, **MQTT**, and **HTTP**.
- **Automation**: Gain experience in automating devices (lights, pumps, watering systems) based on sensor data.
- **Web Development**: Develop a web app to visualize real-time data and control devices remotely.
  
## Project Flow
1. **Room Modules**: Collect data (e.g., temperature, humidity) using sensors and send it to the central dashboard.
2. **Central Dashboard**: Displays the collected data on a physical display and sends it to the web app for remote monitoring.
3. **Web App**: Displays real-time data and allows the user to control devices remotely.
4. **Automation**: Automation logic based on sensor readings controls devices like lights, pumps, and watering systems.

## Getting Started
### Requirements
- **ESP32 microcontrollers**
- Sensors (e.g., DHT22 for temperature and humidity, soil moisture sensors, water temperature sensors)
- OLED/LCD display for central dashboard
- Wi-Fi router for communication between devices
- Web app development tools (e.g., HTML, CSS, JavaScript, MQTT or HTTP for backend)
- Basic knowledge of embedded systems, microcontroller programming, and web development

### Installation
1. **Set up Room Modules**: Connect sensors to the ESP32 and program the module to collect and send data via Wi-Fi.
2. **Set up Central Dashboard**: Use an OLED/LCD display with an ESP32 to show the collected data locally in the living room.
3. **Develop Web App**: Create a web app that listens for data updates from the central dashboard and displays it to the user.
4. **Connect Automation Systems**: Implement control logic for devices such as lights, pumps, and watering systems based on sensor readings.
5. **Integrate Communication**: Use MQTT or HTTP for real-time data synchronization between the room modules, dashboard, and web app.

## Conclusion
The **Connected Home: Automation & Monitoring** project provides hands-on experience in building a smart home system with IoT devices. By integrating embedded systems, automation, and web development, this project offers a comprehensive understanding of how to create a connected and intelligent home environment. It equips learners with practical knowledge in sensor integration, microcontroller programming, IoT protocols, and web app development for real-time control and monitoring.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
