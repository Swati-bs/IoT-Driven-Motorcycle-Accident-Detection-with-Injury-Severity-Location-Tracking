# 🚨 IoT-Driven Motorcycle Accident Detection with Injury Severity & Location Tracking

A smart IoT-based system that detects motorcycle accidents in real-time, monitors rider vitals, classifies injury severity using machine learning, and sends automated alerts to emergency contacts with live GPS location and health data.

---

## 🔧 Tech Stack

**Hardware:**  
- ESP32  
- Accelerometer  
- Heart Rate Sensor  
- Temperature Sensor  
- GPS Module  

**Software:**  
- Python  
- Scikit-learn  
- XGBoost  
- Pandas  
- Matplotlib  

**Machine Learning Model:**  
- XGBoost Classifier (with GridSearchCV tuning) for injury severity classification  

**Deployment:**  
- Serial communication with ESP32  
- CSV-based simulated data pipeline  

---

## 💡 Features

- ✅ Real-Time Accident Detection via sensor thresholding  
- 📍 Location Tracking using GPS module  
- ❤️ Physiological Monitoring: Heart rate, SpO2, Body temperature  
- 🤕 Severity Prediction: Classifies accident as *Minor*, *Moderate*, or *Severe*  
- 🧬 Medical Data Integration: Includes age, asthma, diabetes, allergies, etc.  
- 📲 Automated Alerts (prototype): Sends crash location and severity to emergency contacts  

---

## 📊 Machine Learning Component

- 🧠 Trained on **synthetic + extended health dataset (100 records)**  
- 🔍 Features: Heart Rate, SpO2, Temperature, Age, Asthma, Diabetes  
- ⚙️ Model: XGBoost with hyperparameter tuning (GridSearchCV)  
- ✅ Achieved **100% accuracy** on test data (due to clean synthetic data)  

