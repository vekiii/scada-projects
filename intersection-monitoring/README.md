# SCADA System for Intersection Monitoring

## 📌 Project Overview
This project presents a SCADA-based system for automating the operation of a traffic light intersection and monitoring driver violations and potential traffic incidents. The primary objective is to design a realistic and time-accurate traffic intersection model with integrated supervision and alert handling.

The system simulates real-world traffic behavior using multiple traffic light signals and vehicle representations.

---

## 🚦 Intersection Model
The modeled intersection includes:
- Four traffic lights for motor vehicles
- Eight traffic lights for pedestrians

### Traffic Light Configuration
- Vehicle traffic lights use three LED indicators: red, yellow, and green
- Pedestrian traffic lights use two LED indicators: red and green
- Each traffic light state operates with a predefined duration measured in real time

---

## 🚗 Vehicle Simulation
- The model includes two simulated vehicles: a car and a truck
- Vehicles are controlled using predefined Genie symbols provided by Citect
- Vehicle behavior is synchronized with traffic light states

---

## 🕹️ Control Panels and Alerts
The system includes two control panels, each equipped with:
- An LED indicator signaling alerts or abnormal events
- A STOP button used to acknowledge and deactivate alerts after issues are resolved

---

## 🧠 SCADA Functionality
- Automated traffic light sequencing
- Real-time monitoring of intersection states
- Alert signaling for traffic violations or incidents
- Operator interaction through control panels
- Visualization of vehicles and traffic flow via HMI

---

## 🛠️ Technologies & Tools
- SCADA system for supervision and monitoring
- PLC-based control logic
- Citect SCADA Genie symbols for vehicle simulation
- HMI for intersection visualization and operator control

---

## 📄 Notes
This project was developed as part of academic coursework and focuses on traffic automation, monitoring, and incident supervision using SCADA principles.
