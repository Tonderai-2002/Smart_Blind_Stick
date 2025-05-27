# 👨‍🦯 Smart Blind Stick with Arduino

A low-cost, Arduino-based smart blind stick designed to assist visually impaired individuals in detecting nearby obstacles using an ultrasonic sensor, buzzer, and LED for real-time alerts.

## 📦 Features

- Obstacle detection using ultrasonic sensor
- Audible alert using buzzer
- Visual alert using LED
- Real-time distance display in Serial Monitor

## 🛠 Hardware Required

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Buzzer
- LED
- Resistor (220Ω for LED)
- Breadboard & Jumper Wires
- Power supply (USB or battery pack)

## 🔌 Circuit Connections

| Component        | Arduino Pin |
|------------------|-------------|
| Ultrasonic Trig  | D9          |
| Ultrasonic Echo  | D10         |
| Buzzer           | D11         |
| LED (+)          | D13         |
| LED (–)          | GND via 220Ω resistor |
| Ultrasonic VCC   | 5V          |
| Ultrasonic GND   | GND         |
| Buzzer GND       | GND         |

## 🧠 How It Works

The system continuously measures the distance to the nearest object using the HC-SR04 ultrasonic sensor. 
If the distance is less than or equal to 5 cm, the buzzer and LED are activated, alerting the user to a nearby obstacle.


