# Line-Following-Robot
Built a line following robot using IR sensors and implemented PID-based control logic to maintain accurate path tracking. Optimized motor speed dynamically for smooth and stable movement.
# 🤖 Line Following Robot (PID Based)

## 📌 Overview

This project is a line following robot that uses IR sensors to detect a path and follows it using PID-based control for improved accuracy and stability.

## ⚙️ Components Used

* Arduino Uno / ESP32
* IR Sensors (2 or more)
* Motor Driver (L298N)
* DC Motors
* Chassis + Wheels
* Power Supply

## 🔧 Working

* IR sensors detect the line (black/white surface difference)
* Error is calculated based on sensor readings
* PID algorithm adjusts motor speed dynamically
* Robot maintains smooth and accurate path tracking

## 🧠 Features

* PID-based control system
* Improved stability and reduced oscillations
* Real-time speed adjustment
* Efficient path tracking

## 🚀 Future Improvements

* Add more sensors for better accuracy
* Implement sharp turn handling
* Integrate Bluetooth/WiFi control
* Add obstacle detection along with line following
