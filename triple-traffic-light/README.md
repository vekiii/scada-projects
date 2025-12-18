# SCADA System for Monitoring the Operation of a Triple Traffic Light

## 📌 Project Overview
This project presents a SCADA-based system for monitoring and controlling the operation of a triple traffic light system designed for managing vehicle traffic, pedestrian crossings, and railway crossings.

The system is built around two input devices and seven output signals. Input devices include a switch for detecting the arrival of a train and a second switch used to stop and restart the entire system. Output signals consist of an end-of-cycle indicator and traffic light signals for three separate entities: trains, pedestrians, and vehicles.

---

## ⚙️ System Operation
- When a train is detected, the train signal is activated and remains active while the train is passing.
- During train passage, both pedestrian and vehicle signals are set to red to ensure safety.
- Once the train has passed, the system resumes normal traffic operation.

Under normal conditions:
- Pedestrian and vehicle signals operate alternately.
- When the pedestrian signal is green, the vehicle signal is red, and vice versa.

---

## 🚦 Traffic Control Logic
- Train signal operates independently and has the highest priority.
- Pedestrian signals include red and green states.
- Vehicle signals include red, yellow, and green states.
- An end-of-cycle output indicates completion of each traffic light cycle.

---

## 🔧 Special Operating Modes
- The pedestrian and vehicle signals can be disabled during extended low-traffic periods (e.g., late-night hours).
- This mode allows for system maintenance and reduced power consumption.
- The train signal remains fully operational at all times, regardless of other signal states.

---

## 🧠 SCADA Functionality
- Real-time monitoring of input signals
- Control of traffic light states
- Priority-based event handling (train detection)
- Safe state transitions between traffic phases
- System status visualisation via HMI

---

## 🛠️ Technologies & Tools
- SCADA system for supervision and monitoring
- PLC-based control logic
- HMI interface for traffic system visualisation and control

---

## 📄 Notes
This project was developed as part of academic coursework and focuses on safety-critical control logic implemented using SCADA principles.

