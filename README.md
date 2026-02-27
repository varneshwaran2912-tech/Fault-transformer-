# ⚡ Transformer Line Fault Detection & Monitoring System

## 📌 Project Overview
This project is a Transformer Line Monitoring and Fault Detection System using ESP32.  
It monitors voltage levels of three transformers and detects fault conditions in real-time.

The system can:
- Measure transformer voltage
- Detect low voltage fault condition
- Display status on website
- Send alerts (optional: Blynk / SMS)

---

## 🛠 Components Used
- ESP32 Dev Module
- Voltage Sensor Module (ZMPT101B)
- Current Sensor (ACS712) (optional)
- 5V Power Supply
- Connecting Wires
- WiFi Network

---

## 🌐 Web Monitoring
A live monitoring dashboard is created using HTML.

Website Features:
- Displays Voltage of 3 Transformers
- Shows Normal / Fault Status
- Mobile Responsive Design
- Fault Simulation Option

---

## 🚀 How It Works
1. Voltage sensor measures transformer output.
2. ESP32 reads analog voltage.
3. If voltage < 180V → Fault detected.
4. Data displayed on website dashboard.

---

## 📷 Project Output
Transformer 1: Voltage + Status  
Transformer 2: Voltage + Status  
Transformer 3: Voltage + Status  

---

## 🔮 Future Improvements
- Firebase Cloud Integration
- Real-time Graph Monitoring
- SMS Alert System
- Mobile App Integration

---

## 👨‍💻 Developed By
Varneshwaran  
ECE Student  
Transformer Monitoring Project
