# Automatic-Plant-Watering-system
# 🌱 Smart Plant Watering System

A simple **IoT-based automatic plant watering system** that monitors soil moisture and waters the plant only when needed. The system also displays real-time moisture values and motor status on a **Tkinter-based GUI**.

This project combines **hardware (ESP32/NodeMCU)** and **software (Python GUI)** to reduce water wastage and make plant care smart and automatic.

---

## 🚀 Features

* Automatic watering based on soil moisture level
* Real-time soil moisture display
* Motor/Pump ON–OFF status shown on GUI
* Simple and beginner-friendly design
* No manual switch required (fully automatic)

---

## 🛠️ Tech Stack

### Hardware

* ESP32 / NodeMCU
* Soil Moisture Sensor
* Relay Module
* Water Pump
* Power Supply

### Software

* Python
* Tkinter (GUI)
* Serial Communication (UART)
* Arduino IDE

---

## 🧠 Working Principle

1. The soil moisture sensor measures moisture level in the soil.
2. ESP32 reads the sensor value.
3. If moisture is below a threshold → motor turns ON.
4. If moisture is sufficient → motor turns OFF.
5. Moisture value and motor status are sent to PC.
6. Tkinter GUI displays the data in real time.



---


## ⚙️ How to Run

### Hardware Setup

1. Connect soil moisture sensor to ESP32.
2. Connect relay module and water pump.
3. Upload Arduino code using Arduino IDE.

### Software Setup

```bash
pip install pyserial
```


---

## 🎯 Applications

* Home gardening
* Smart agriculture
* Indoor plants
* Water conservation systems

---

## 📌 Future Improvements

* Mobile app integration
* Cloud monitoring (Firebase / Thingspeak)
* Multiple plant support
* ML-based watering prediction

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🤍 Acknowledgement

Made as a mini IoT project for learning embedded systems, Python GUI, and automation.

---

⭐ If I like this project, don’t forget to **star the repository**!
