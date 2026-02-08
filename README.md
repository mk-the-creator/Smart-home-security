# Laser Light Security System with Fingerprint Sensor 🔐🔦

## 📌 Project Overview
This project implements a **dual-layer security system** that combines **biometric authentication** and **laser-based intrusion detection**.  
Access is granted only to authorized users through a fingerprint sensor, while a laser–LDR setup continuously monitors for unauthorized intrusions.

The system is designed to be **low-cost, reliable, and automated**, making it suitable for homes, offices, laboratories, and high-security areas.

---

## 🎯 Objectives
- Design a **low-cost and reliable laser security system**
- Eliminate the need for human intervention
- Detect intrusions in **real time**
- Combine **fingerprint authentication** with **laser-based monitoring**
- Improve security in high-risk environments

---

## 🛠️ Components Used
- Arduino UNO
- R307S Fingerprint Sensor
- Laser Light Module
- Light Dependent Resistor (LDR)
- 5V Relay Module
- BC547 Transistor
- Buzzer
- 10kΩ Resistor
- Breadboard & Connecting Wires
- 5V Power Supply

---

## ⚙️ Working Principle
1. The **fingerprint sensor** captures and verifies the user’s fingerprint.
2. If the fingerprint is **authorized**:
   - Arduino activates the relay.
   - Laser is temporarily turned OFF to allow safe passage.
3. If the fingerprint is **unauthorized**:
   - Laser remains active.
4. If the **laser beam is interrupted** without authorization:
   - LDR detects the change.
   - Buzzer is triggered as an alarm.

This ensures **dual-layer protection**:
- Authentication + Intrusion Detection.

---

## 🧠 Technologies & Tools
- Arduino IDE
- Proteus (for simulation)
- Embedded C / Arduino programming
- Basic Electronics (Transistors, Relays, Sensors)
- Git & GitHub (version control)

---

## 📂 Repository Contents
- 📑 Project PPT / Report
- 📊 Circuit diagrams & block diagrams
- 🧪 Simulation screenshots
- 📘 Documentation

*(Arduino source code can be added later)*

---

## ✅ Advantages
- Dual-layer security system
- Fully automated operation
- Low power consumption
- Cost-effective components
- Scalable and customizable
- Suitable for IoT expansion

---

## 🏢 Applications
- Homes & apartments
- Offices & warehouses
- Data centers & research labs
- Banks & ATMs
- Educational institutions
- Industrial plants
- Restricted-access areas

---

## 🔮 Future Scope
- IoT integration (SMS / App alerts)
- Camera-based intruder capture
- AI-based intrusion analysis
- Wireless and cloud-based monitoring
- Energy-efficient system upgrades


## 🏫 Institution
**Amrita Vishwa Vidyapeetham, Amritapuri Campus**  
B.Tech – Artificial Intelligence & Data Science  
Course: *Introduction to Electrical Engineering (23EEE103)*
