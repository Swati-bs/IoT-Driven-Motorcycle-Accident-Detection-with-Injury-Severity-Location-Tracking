# 🚨 IoT-Driven Motorcycle Accident Detection  
### Injury Severity Classification | GPS Location Tracking | Vitals Monitoring  

A smart IoT system that detects motorcycle accidents in real-time, monitors rider vitals, classifies injury severity using machine learning, and sends automated alerts to emergency contacts with GPS coordinates and health data.

---

## 🔧 Tech Stack

**Hardware Components**
- 🧠 ESP32 Microcontroller  
- 📉 Accelerometer  
- ❤️ Heart Rate Sensor  
- 🌡️ Temperature Sensor  
- 📍 GPS Module  

**Software & Tools**
- 🐍 Python  
- 📊 Scikit-learn, XGBoost, Pandas, Matplotlib  
- 🛠️ GridSearchCV for model tuning  
- 💬 Serial Communication with ESP32  
- 📁 CSV-based Data Pipeline (real-time + simulated)  

---

## 💡 Key Features

- ✅ **Accident Detection** — Detects impact using accelerometer thresholding  
- 📍 **GPS Tracking** — Captures and logs crash location  
- ❤️ **Vitals Monitoring** — Records Heart Rate, SpO2, and Body Temperature  
- 🤕 **Injury Severity Prediction** — Classifies as *Minor*, *Moderate*, or *Severe*  
- 🧬 **Medical Data Integration** — Includes Age, Asthma, Diabetes, Allergies  
- 📲 **Emergency Alerts** *(Prototype)* — Sends crash severity and location to contacts  

---

## 📊 Machine Learning Component

- 🧠 Trained on a **hybrid dataset of 500+ samples**
  - ✅ Real-time sensor data  
  - 🧪 Synthetic samples covering rare crash cases  
- 🔍 Input Features:
  - Heart Rate, SpO2, Temperature  
  - Age, Asthma, Diabetes  
- ⚙️ **Model:** XGBoost Classifier with hyperparameter tuning (GridSearchCV)  
- ✅ Achieved **~99% accuracy** on clean test set
- https://colab.research.google.com/drive/1oJ8RWXNaWO3y7PalyYVX-7anUL0RUEII?usp=sharing
