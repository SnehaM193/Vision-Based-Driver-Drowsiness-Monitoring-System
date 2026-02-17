# 🚗 Vision-Based-Driver-Drowsiness-Monitoring-System
An Arduino-based embedded safety system that detects prolonged eye closure using an eye-blink sensor and triggers alerts to prevent potential accidents. The system activates a buzzer and controls a motor via relay when drowsiness is detected.

## 📌 Features
- Eye-blink sensor for fatigue detection  
- Buzzer alert for warning  
- Relay-based motor control  
- Dual power supply architecture  
- Hardware-software integration  

## ⚙️ Hardware Components
- Arduino UNO  
- Eye-Blink Sensor  
- Relay Module (SPDT)  
- Buzzer  
- DC Motor + Wheels  
- 2 × 9V Batteries  
- Jumper Wires

## 🔌 Circuit Connections

- Eye-Blink Sensor → VCC to 5V, GND to GND, OUT to D2  
- Relay Module → VCC to 5V, GND to GND, IN to D8  
- Buzzer → + to D9, – to GND  
- DC Motor → Connected to external 9V battery through relay  
- Power Supply → Separate 9V batteries for Arduino and motor



## 🚀 Working Principle

1. The driver wears the eye-blink sensor.
2. Sensor detects eye closure.
3. If eyes remain closed beyond threshold:
   - Buzzer activates
   - Relay cuts off motor power
4. When eyes reopen, system resets automatically.


## 🔧 Tech Stack

- Arduino UNO
- Embedded C
- Digital Eye-Blink Sensor
- Relay Module
- DC Motor Control

## 📜 License

This project is licensed under the MIT License.
