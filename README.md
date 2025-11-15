🌍 Air Quality Monitoring System – IoT Project

A real-time IoT-based Air Quality Monitoring System that measures Air Quality, Temperature, and Humidity using ESP32, MQ135, and DHT11.
Sensor data is uploaded to the ThingSpeak Cloud and displayed on a custom-built web dashboard with live graphs and an alert system.

📌 Features

Real-time Air Quality Monitoring
Temperature & Humidity Measurement
Cloud Upload via ThingSpeak
Professional Live Dashboard (HTML, CSS, JS)
API-based data fetching
Graphs & Status Indicators

Air Quality Classification:

Good: 0–100
Moderate: 101–200
Bad: 200+
Automatic Buzzer Alert for Bad Air Quality
Clean UI with icons and images

📸 Dashboard Preview
<img width="1271" height="887" alt="image" src="https://github.com/user-attachments/assets/d857c613-6728-401e-8384-a20d6ff3e51c" />

🧩 Components Used
Controller
ESP32 (Simulated in Wokwi)
Built-in WiFi
Fast processing
Suitable for IoT cloud integration

Sensors

MQ135 – Air Quality Sensor
DHT11 – Temperature & Humidity Sensor

Output Device

Buzzer – Alerts when AQI > 200

⚙️ Working Principle

MQ135 reads air quality
DHT11 measures temperature & humidity
ESP32 processes values and connects to WiFi
Data is uploaded to ThingSpeak Cloud using HTTP requests
Our website fetches live data using ThingSpeak Read API
Values, graphs, and status indicators update automatically
If AQI > 200 → Buzzer turns ON

☁️ IoT & Cloud Integration

Used ThingSpeak Cloud to store data in fields
Real-time data visualization
JSON API used for website dashboard
Website updates without refresh using fetch()

📊 Fields Used (ThingSpeak)

Field 1: Temperature (°C)
Field 2: Humidity (%)
Field 3: Air Quality (MQ135)

🖥️ Website Dashboard

Built using:

HTML
CSS
JavaScript
ThingSpeak API
Color-coded cards & icons
Real-time chart display

📁 Project Structure
Air-Quality-Monitoring-IoT/
│
├── ESP32_Code/
│   └── air_quality_monitor.ino
│
├── Website/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── images/
│   └── (dashboard icons & preview)
│
└── Presentation/
    └── Air_Quality_Presentation.pptx

🚀 How to Run
1. Upload ESP32 code in Wokwi
Add ESP32, MQ135, DHT11
Paste code
Enter WiFi + ThingSpeak API Key
Run simulation

2. View data on ThingSpeak

Open your channel
Check field updates

3. Run Website Dashboard

Open index.html
Site will auto-fetch live readings

📌 Applications

mart Cities
Homes & Offices
Schools & Hospitals
Research Labs
Pollution Monitoring

🏁 Conclusion

This project successfully demonstrates how IoT, sensors, cloud platforms, and web technologies can be integrated to build a real-time environmental monitoring system. It is scalable, accurate, and suitable for practical applications in smart environments.
