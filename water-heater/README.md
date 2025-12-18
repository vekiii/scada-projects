# SCADA System for Monitoring and Control of a Water Heater

## 📌 Project Overview
This project implements a SCADA-based system for monitoring and controlling a water heater used for heating cold water and distributing hot water to an outlet, such as a faucet, shower, or sprinkler, depending on the system configuration.

The system features two main HMI screens — a Menu screen and a Main screen — along with built-in system pages for alarms and trends, enabling comprehensive monitoring and supervision of the heating process.

---

## ⚙️ System Description
The water heater is equipped with two level indicators:
- Hot water indicator (red)
- Cold water indicator (blue)

The system is connected to three primary pipelines:
- Cold water inlet, controlled by an automatic valve
- Power supply connection (battery or external power source)
- Hot water outlet for water distribution

---

## 🔥 Operating Principle
- Cold water is used exclusively for heating.
- Hot water production begins only after the cold-water tank is completely filled.
- The total system capacity is 50 liters of cold water and 50 liters of hot water.
- Heating 50 liters of hot water consumes approximately 38 liters of cold water.

---

## ⚡ Heating Control Logic
- One, two, or three heating elements are activated depending on the current hot water level.
- Heating intensity is dynamically adjusted to optimize energy usage and system performance.

---

## 🚰 Water Level Management
- When the cold-water level drops below 20 liters, the inlet valve opens automatically.
- Cold water refilling occurs without interrupting hot water distribution.
- Hot water can continue to be consumed until fully depleted.
- Once refilled, the heating process restarts automatically.

---

## 🧠 SCADA Functionality
- Real-time monitoring of water levels and system status
- Automated valve control
- Dynamic heating element activation
- Alarm handling and trend visualization
- User interaction via HMI screens

---

## 🛠️ Technologies & Tools
- SCADA system for monitoring and control
- PLC-based control logic
- HMI for visualization, alarms, and trends

---

## 📄 Notes
This project was developed as part of academic coursework and demonstrates SCADA-based control of a dynamic water heating and distribution process.
