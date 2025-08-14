# CropCare-Sensor-Hub

An IoT-powered farm monitoring system using Arduino/ESP devices with temperature, humidity, and soil moisture sensors.  
Data is transmitted via MQTT and visualized in a dashboard for real-time monitoring and decision-making.

## 🚀 Features
- Live temperature, humidity, and soil moisture readings
- MQTT-based IoT communication
- Historical data visualization
- Configurable alert thresholds

## 🛠 Tech Stack
- Hardware: Arduino / ESP8266, DHT11, YL69
- Backend: Java 17, Spring Boot, MQTT
- Dashboard: React or ThingsBoard
- Database: TimescaleDB (prod) / H2 (dev)
- Version Control: Git + GitHub

## 📂 Structure
- `/hardware` – Arduino/ESP code
- `/backend` – Spring Boot API
- `/dashboard` – UI or integration scripts

## 🧑‍💻 Setup
```bash
# Backend
mvn spring-boot:run
# Hardware
Upload Arduino sketches to device
