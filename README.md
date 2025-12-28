# Smart Parking Slot Monitoring System

A 3-slot smart parking demo using ESP32, ultrasonic sensors, and IoT.

## Features
- Detects occupancy with HC-SR04 ultrasonic sensors (5 cm threshold).
- Red LEDs indicate occupied slots.
- Sends real-time data to ThingSpeak via Wi-Fi.
- Simple web map showing availability, with directions from entrance/mall door.
- QR code for quick access on phones.

## Hardware
- ESP32-DevKitC
- 3 × HC-SR04 ultrasonic sensors
- 3 × Red LEDs (with resistors)
- Breadboard and jumper wires
- Voltage dividers on Echo pins

## Wiring
[Describe your pins or add a photo/diagram]

## Setup
1. Upload the code (see main.ino).
2. Update Wi-Fi SSID/password and ThingSpeak API key.
3. Visit the web map: [your GitHub Pages URL]
4. Scan QR code for mobile access.

## Website/Map
Hosted on GitHub Pages: Live parking map with green/red slots.

## License
MIT License
