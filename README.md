# Air Pollution Monitoring System Using IoT

## Abstract
Air pollution has become one of the major environmental problems affecting human
health and ecosystem balance. Continuous monitoring of air quality is essential
to control pollution levels. This project presents an IoT-based air pollution
monitoring system that measures air quality in real time using gas sensors.
The collected data helps in identifying pollution levels and taking preventive
actions.

---

## Introduction
Rapid urbanization and industrial growth have resulted in increased air pollution.
Traditional air quality monitoring systems are expensive and lack real-time
availability. The proposed system uses low-cost IoT components to monitor air
pollution effectively and continuously.

---

## Objectives
- To monitor air quality using gas sensors
- To measure temperature and humidity
- To display real-time pollution data
- To identify high pollution conditions
- To develop a cost-effective IoT solution

---

## Hardware Requirements
- NodeMCU ESP8266
- MQ-135 Gas Sensor
- DHT11 Temperature and Humidity Sensor
- Breadboard
- Jumper Wires
- USB Cable

---

## Software Requirements
- Visual Studio Code
- Arduino Extension for VS Code
- Arduino IDE (for drivers and libraries)
- DHT Sensor Library

---

## System Architecture
The MQ-135 sensor detects harmful gases and sends analog data to the NodeMCU.
The DHT11 sensor provides temperature and humidity values. NodeMCU processes
the data and displays results through the Serial Monitor.

---

## Methodology
1. Initialize sensors and microcontroller
2. Read air quality, temperature, and humidity values
3. Process sensor data
4. Compare air quality with threshold values
5. Display results on Serial Monitor
6. Generate warning for high pollution

---

## Implementation
The system is implemented using NodeMCU and programmed using Arduino framework
in Visual Studio Code. The sensors are interfaced and calibrated for accurate
data measurement.

---

## Results
The system successfully monitored air pollution levels and detected changes
in air quality. High pollution values generated warnings, indicating unsafe
conditions.

---

## Applications
- Smart City Pollution Monitoring
- Environmental Monitoring
- Industrial Safety Systems
- Smart Homes

---

## Advantages
- Low cost
- Real-time monitoring
- Easy to install
- Scalable system

---

## Conclusion
The IoT-based Air Pollution Monitoring System provides an efficient, low-cost
solution for real-time monitoring of air quality. It helps in early detection
of pollution levels and supports environmental protection.

---

## Future Scope
- Cloud data storage
- Mobile application monitoring
- SMS or email alerts
- Advanced analytics


---
