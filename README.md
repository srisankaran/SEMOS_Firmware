# ⚡ SEMOS — Smart Energy Meter  
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Build](https://img.shields.io/badge/Build-Stable-brightgreen.svg)]()
[![Platform](https://img.shields.io/badge/Platform-ESP32-orange.svg)]()
[![Status](https://img.shields.io/badge/Version-1.0-lightgrey.svg)]()

### 👩‍🔬 Developed by **Ojo & Sri**

---

## 📘 Overview  
**SEMOS (Smart Energy Meter for Optimized Systems)** is an intelligent IoT-based energy monitoring solution designed to measure and analyze electrical parameters in real time.  
It integrates precision sensors, an ESP32 microcontroller, and a user-friendly web dashboard to enable efficient energy tracking and remote access.

...

## ⚙️ Key Features  
✅ Real-time measurement of voltage, current, power, and energy  
✅ Automatic data logging and timestamping  
✅ Wi-Fi connectivity for remote monitoring  
✅ Integrated web interface for visualization  
✅ Data export in `.CSV` and `.TXT` formats  
✅ Over-The-Air (OTA) firmware updates  
✅ Compact and reliable hardware design  



## 🧠 System Highlights  
- Modular firmware supporting multiple PZEM and sensor units  
- Supports both Access Point and Station (client) modes  
- Real-time data updates without page reload  
- Secure and stable data transfer to local servers  
- Designed for continuous 24×7 operation  



## 🛠️ Hardware Requirements  
- **ESP32** (any variant)  
- **PZEM-004T v3.0** or compatible energy sensor  
- **SD card module** (optional for local storage)  
- **Power supply** (regulated 5V DC)  
- Optional: OLED / LCD display for live readout  



## 💻 Software Requirements  
- **Arduino IDE** or **PlatformIO**  
- Libraries used:  
  - `WiFi.h`  
  - `HTTPClient.h`  
  - `ArduinoJson.h`  
  - `PZEM004Tv30.h`  
  - `ArduinoOTA.h`  



## 🚀 Getting Started  
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/SEMOS.git
