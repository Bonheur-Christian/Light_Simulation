# MQTT Light Control

This is a simple web-based MQTT light control system that allows users to turn a light ON or OFF. The project simulates an IoT device (ESP8266) using Python, which listens for MQTT messages and prints the status.

## Features
- Web interface with ON/OFF buttons
- Uses MQTT.js for publishing messages over WebSockets
- Python script simulates an ESP8266, listening for MQTT messages
- Uses  MQTT broker

## Setup & Running
### 1. Run the Python script (IoT Device)
```sh
python light_simulation.py
```
### 2. Open `index.html` file in Browser to stimulate user interface
