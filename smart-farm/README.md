# SCADA System for Monitoring and Control of a Smart Farm

## 📌 Project Overview
This project presents a SCADA-based Smart Farm system designed to automate and monitor key farm processes with the goal of optimizing living conditions for animals and increasing overall operational efficiency.

The system integrates multiple independent subsystems that continuously monitor and regulate essential environmental and operational parameters, providing a centralized supervision and control solution.

---

## 🧩 System Architecture
The Smart Farm system consists of the following subsystems:
- Resource dosing system (food and water)
- Air quality monitoring system
- Temperature regulation system
- Access detection and alarm system

Each subsystem operates autonomously while being supervised through a central SCADA interface.

---

## 🌾 Resource Dosing System
- Level sensors monitor food and water container levels.
- When a low level is detected:
  - A solenoid valve refills water from the boiler.
  - A food dispenser delivers food automatically.
- After five consecutive dosing cycles, an LED indicator signals that food storage requires manual replenishment.

---

## 🌬️ Air Quality Monitoring System
- Continuous monitoring of air quality parameters, including:
  - Harmful gas concentrations (e.g., ammonia, hydrogen sulfide)
  - Humidity levels
- An air purifier is automatically activated when measured values exceed acceptable thresholds to maintain optimal air quality.

---

## 🌡️ Temperature Regulation System
- A temperature sensor provides real-time feedback.
- The system maintains temperature within a predefined range.
- Heating or ventilation devices (heater or fan) are automatically switched on or off based on deviations from the setpoint.

---

## 🚨 Access Detection Alarm System
- Perimeter monitoring is implemented using:
  - Passive Infrared (PIR) sensors, or
  - Motion detection sensors (e.g., ultrasonic sensors)
- In the event of unauthorized access:
  - An audible alarm (siren) is triggered to notify operators.

---

## 🧠 SCADA Functionality
- Centralized monitoring of all subsystems
- Automated control logic based on sensor feedback
- Alarm handling and event notification
- Real-time system status visualization via HMI
- Improved efficiency and animal welfare through automation

---

## 🛠️ Technologies & Tools
- SCADA system for supervision and control
- PLC-based control logic
- Sensors and actuators for environmental and process control
- HMI for visualization and user interaction

---

## 📄 Documentation
- Detailed project report available in `izvestaj.docx`

---

## 📄 Notes
This project was developed as part of academic coursework and demonstrates the application of SCADA systems in smart agriculture and automated farm management.
