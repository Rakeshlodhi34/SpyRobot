# 🤖 Spy Robot using ESP32-CAM for Surveillance

A compact, Wi-Fi-enabled surveillance robot built using the ESP32-CAM module. Designed for real-time video streaming and remote navigation, this project is ideal for security monitoring in inaccessible or hazardous areas.

## 🔍 Project Overview

This project demonstrates the development of a **Spy Robot** that uses an **ESP32-CAM module**, **Arduino UNO**, and motor drivers to perform live video surveillance. The robot can be controlled wirelessly via a smartphone or computer, offering a low-cost solution for remote monitoring applications.

## 🎯 Features

- 📷 Real-time video streaming using ESP32-CAM
- 🌐 Wi-Fi-based remote control through smartphone or web interface
- 🔋 Low power consumption
- 🚗 Obstacle avoidance and movement in all directions
- 🔧 Easily customizable and expandable

## 🛠️ Hardware Components

- ESP32-CAM Module
- Arduino UNO
- L298N Motor Driver
- DC Motors (x2)
- Chassis and Wheels
- Li-ion Battery (or 9V battery)
- Jumper Wires
- Breadboard (optional)

## 🧠 Software Requirements

- Arduino IDE
- ESP32 board support in Arduino IDE
- Libraries:
  - `WiFi.h`
  - `ESPAsyncWebServer.h`
  - `esp_camera.h`

## 📡 Circuit Diagram

> Add your Fritzing diagram or image here (e.g., ![Circuit Diagram](path/to/image.png))

## 🚀 Getting Started

1. **Install ESP32 Board Support**
   - In Arduino IDE, go to `File > Preferences` and add this URL in "Additional Board Manager URLs":
     ```
     https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
     ```

2. **Select Board and Port**
   - Board: `AI Thinker ESP32-CAM`
   - Port: Select the appropriate COM port

3. **Upload Code**
   - Connect ESP32-CAM to your PC using a USB-to-TTL converter.
   - Press and hold the **IO0 (Flash)** button while uploading.

4. **Control the Robot**
   - Once powered, the ESP32 will connect to your Wi-Fi and display the streaming IP address in the Serial Monitor.
   - Open the IP in a browser to access the video feed and control panel.

## 🧾 Folder Structure


## 📽️ Demo

 [Watch Demo](https://youtube.com/shorts/E0mk4sn4zHc?si=AQHAIDRSvmSpTWom))

## 💡 Applications

- Home Security
- Border Surveillance
- Disaster Recovery
- Industrial Monitoring
- Military Reconnaissance

## 🤝 Contribution

@kritikagithubtripathi
Ashish Barpete 
Rakesh Lodhi

supervisor: Dr. soumitra K. Nayak

