# Sensor-Based-Electronic-Nose-for-COVID-19-Detection
A smart eNose system using gas sensors and AI to detect COVID-19 from human breath. It analyzes VOC patterns for rapid, non-invasive screening.
Here’s a concise and professional **GitHub-ready README.md** for your project 👇

---

# 🤖 Sensor-Based Electronic Nose for COVID-19 Detection

A smart **Electronic Nose (eNose)** system that uses an array of **gas and VOC sensors** to detect breath biomarkers associated with **COVID-19 infection**. The sensor data is analyzed using **machine learning algorithms** to identify infection patterns quickly and non-invasively.

---

## ⚙️ Features

* Detects volatile organic compounds (VOCs) in exhaled breath
* Uses multiple gas sensors for pattern recognition
* AI/ML model for COVID-19 classification
* Real-time data acquisition and visualization
* Low-cost, portable, and non-invasive testing approach

---

## 🧩 Components

* Arduino / ESP32 Microcontroller
* MQ-Series Gas Sensors (e.g., MQ-3, MQ-135, MQ-4, MQ-7)
* Analog-to-Digital Converter (if required)
* LCD Display / Serial Monitor
* Power Supply and Enclosure

---

## 💻 Working Principle

1. A person exhales near the **sensor array (eNose chamber)**.
2. Gas sensors detect changes in air composition (VOCs, CO₂, NH₃, etc.).
3. Sensor readings are digitized and sent to the microcontroller.
4. The data is processed and classified by a trained **ML model** (e.g., SVM, Random Forest).
5. The system outputs “COVID Positive” or “COVID Negative” based on the predicted result.

---

## 🧠 Tools & Technologies

* **Arduino IDE** for data acquisition
* **Python (Scikit-learn, Pandas, Matplotlib)** for model training
* **Serial Communication (UART)** for data transfer
* **Proteus / Tinkercad** for circuit simulation (optional)

---

## 📊 Output

* Real-time VOC readings on LCD / Serial Monitor
* Classification result displayed as:

  * ✅ **Normal / COVID Negative**
  * ⚠️ **Abnormal / COVID Positive**

---

## 🧾 Applications

* Rapid health screening in hospitals, airports, or offices
* Non-invasive diagnostics for respiratory diseases
* Integration with mobile or IoT-based health platforms

---

## 📜 License

Open-source project for **research and educational purposes**.

---


