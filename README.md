# Floating-sensor-based-system-for-automatic-reading-and-transmission-of-water-levels-in-rivers
Our solution is an automated floating sensor system designed to monitor river water quality and hydrology in real-time. It provides early flood alerts and proactive environmental management through a self-sufficient, solar-powered module.
### SIH 2025 
* Team AgriNova (ID: 68904)
* Theme: Disaster Management
* Problem Statement: Development of a floating sensor-based system for automatic reading and transmission of water levels in rivers (ID: 25249)
### Overview
Our solution is an automated floating sensor system designed to monitor river water quality and hydrology in real-time. It provides early flood alerts and proactive environmental management through a self-sufficient, solar-powered module.
### Key Features
* Multi-Sensor Redundancy: Uses Ultrasonic (Maxbotix MB7040), Radar, and Pressure sensors for accurate readings ($\pm1$ cm accuracy).
* Predictive Analytics: Integrated Machine Learning analyzes data to predict water levels 24-48 hours in advance.
* Hybrid Communication: Seamless data transmission via LoRaWAN, GSM/GPRS (LTE-M), and even Satellite for extreme remote areas.
* Rugged Design: IP68-rated enclosure made of ABS plastic, anchored with Kevlar ropes to withstand turbulent currents.
* Energy Autonomy: Solar-powered with a 30-day battery backup and low-power sleep cycles.
### Technical StackHardware
* Microcontrollers: Cortex-M (Data Acquisition) and ESP32 (Control & Communication).
* Sensors: Ultrasonic, Pressure Array ($\pm0.05\%$ FS accuracy), pH, Temperature, and High-precision GPS.
* Power: Solar panels + Lithium-graded batteries.
* SoftwareCloud: Azure/AWS for data ingestion.
* Web Dashboard: Live Prototype Link.
* Protocol: LoRaWAN & MQTT for efficient data packets.
### How It Works
* Sense: Sensors collect level, flow, and quality data every 5 minutes.
* Process: ESP32 performs noise filtration and data compression.
* Transmit: Data is sent via LoRa or Cellular to a central gateway.
* Analyze: Cloud-based ML models generate flood alerts and real-time insights.
