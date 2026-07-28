# 🌱 Smart Plant Monitoring System

An IoT-based Smart Plant Monitoring System built using **ESP8266 NodeMCU** that monitors soil moisture, temperature, humidity, and light intensity in real time. The system automatically controls a water pump based on soil moisture levels and allows users to monitor and control the system remotely using the **Blynk IoT Platform**.

---

## 🚀 Features

- 🌱 Real-time Soil Moisture Monitoring
- 🌡️ Temperature & Humidity Monitoring
- ☀️ Light Intensity Detection
- 💧 Automatic Water Pump Control
- 📱 Remote Monitoring using Blynk IoT
- 📟 LCD Display for Live Sensor Data
- 🔔 Smart Alerts and Notifications
- ⚡ Low Power Consumption
- 🌍 Suitable for Home Gardens and Agriculture

---

## 🛠️ Hardware Components

- ESP8266 NodeMCU
- Soil Moisture Sensor
- DHT11 Temperature & Humidity Sensor
- LDR (Light Dependent Resistor)
- Relay Module
- Mini Water Pump
- 16x2 I2C LCD Display
- Jumper Wires
- Breadboard
- Power Supply

---

## 💻 Software Requirements

- Arduino IDE
- ESP8266 Board Package
- Blynk IoT
- ESP8266WiFi Library
- Blynk Library
- LiquidCrystal_I2C Library
- DHT Sensor Library

---

## ⚙️ Working

1. ESP8266 continuously reads data from the soil moisture, temperature, humidity, and light sensors.
2. Sensor values are displayed on the LCD.
3. Data is uploaded to the Blynk Cloud.
4. When soil moisture falls below the threshold, the relay turns ON the water pump.
5. Once the soil reaches the required moisture level, the relay switches OFF the pump automatically.
6. Users can monitor and control the system remotely using the Blynk mobile application.

---

## 📊 System Architecture

```
                Soil Moisture Sensor
                         │
                         ▼
                  ESP8266 NodeMCU
                 ┌────────┼────────┐
                 ▼        ▼        ▼
             DHT11      LCD     Blynk Cloud
                 │                 │
                 ▼                 ▼
        Temperature & Humidity  Mobile App
                         │
                         ▼
                    Relay Module
                         │
                         ▼
                     Water Pump
```

---

## 📂 Folder Structure

```
Smart-Plant-Monitoring-System/
│
├── Code/
│   └── SmartPlantMonitoring.ino
│
├── Circuit/
│   ├── Circuit_Diagram.png
│   └── Block_Diagram.png
│
├── Images/
│   ├── Prototype.jpg
│   ├── LCD_Output.jpg
│   └── Blynk_Dashboard.png
│
├── Documentation/
│   └── Smart_Plant_Monitoring_Report.pdf
│
├── README.md
└── LICENSE
```

---

## 📱 Blynk Dashboard

The Blynk dashboard displays:

- Soil Moisture (%)
- Temperature (°C)
- Humidity (%)
- Water Pump Status
- Live Sensor Readings
- Manual Pump Control

---

## ▶️ How to Run

1. Install Arduino IDE.
2. Install the ESP8266 Board Package.
3. Install all required libraries.
4. Create a project in Blynk IoT.
5. Replace the following in the code:
   - Blynk Auth Token
   - Wi-Fi SSID
   - Wi-Fi Password
6. Upload the code to the ESP8266.
7. Connect the hardware according to the circuit diagram.
8. Open the Blynk App and start monitoring your plant.

---

## 📈 Results

- Real-time monitoring of environmental conditions
- Automatic irrigation based on soil moisture
- Water conservation
- Remote monitoring through mobile application
- Reduced manual effort
- Improved plant health

---

## 🔮 Future Scope

- AI-based Plant Disease Detection
- Machine Learning for Smart Irrigation
- Cloud Data Analytics
- Weather Forecast Integration
- Solar Powered System
- Camera-based Plant Monitoring
- Voice Assistant Integration
- Multiple Plant Monitoring

---

## 👨‍💻 Team Members

- **R. Rohith**
- **M. Raviteja Reddy**
- **M. Rishik Reddy**
- **D. Ram Choudary**

Department of Electronics & Communication Engineering  
Koneru Lakshmaiah Education Foundation (KLEF)

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

## ⭐ Support

If you found this project useful, please ⭐ star this repository and share it with others.

---

## 📧 Contact

For any queries or suggestions, feel free to create an Issue or Pull Request.
