#  AuraBandX: A Wearable Device for Seizure Detection and Health Monitoring

**AuraBandX** is a smart wearable device designed to **detect seizures** and **monitor vital signs** in real-time.  
It integrates multiple sensors with an **ESP32 microcontroller** to continuously track key health parameters and alert caregivers during abnormal readings or seizure events.

---

##  Project Overview

Epilepsy and sudden health irregularities often require continuous monitoring, especially for patients with recurring episodes.  
**AuraBandX** provides a low-cost, IoT-based solution that uses **sensor fusion, wireless communication, and real-time alerting** to ensure patient safety and early detection of potential seizures.

The device continuously collects data from motion, temperature, and heart rate sensors and transmits it to a **web interface** for remote monitoring.

---

##  Objectives

- To design a **wearable IoT device** capable of detecting seizure-like motion patterns.  
- To continuously monitor **vital parameters** such as body temperature and heart rate.  
- To implement a **real-time alert system** using a buzzer and web notifications.  
- To build an affordable, scalable, and user-friendly **health monitoring solution**.

---

##  Key Features

✅ **Real-time vital tracking** (motion, temperature, heart rate)  
✅ **Seizure detection** using motion sensor patterns  
✅ **Instant alert** via buzzer when abnormal readings occur  
✅ **Wi-Fi connectivity** for live data monitoring  
✅ **Web interface dashboard** for visualization and data logs  
✅ **Low-cost, wearable, and battery-powered design**

---


## System Flow

```text
[ Sensors: MPU6050, DHT11, Heart Rate ]
           ↓
[ ESP32 Microcontroller ]
           ↓
[ Wi-Fi Transmission ]
           ↓
[ Web Dashboard / Cloud Storage ]
           ↓
[ Alert System (Buzzer + Notification) ]
```
## 🔩 Hardware Components

| Component | Function |
|------------|-----------|
| **ESP32** | Main microcontroller with Wi-Fi capability |
| **MPU6050** | Detects motion and sudden body movements |
| **Heart Rate Sensor (MAX30102 or Pulse Sensor)** | Monitors heartbeat and SpO₂ |
| **DHT11 Sensor** | Measures body temperature and environment temperature |
| **Buzzer** | Alerts during abnormal readings |
| **Power Supply** | Battery-operated for portability |

---

## 🧠 Software & Tools Used

| Category | Tools |
|-----------|-------|
| Programming | Arduino IDE, C/C++ |
| Communication | Wi-Fi (HTTP / MQTT) |
| Web Dashboard | HTML, CSS, JavaScript, Flask / ThingSpeak |

---

## Demo


https://github.com/user-attachments/assets/63b58e4d-e692-42e5-aa7c-da39ddd2774f
