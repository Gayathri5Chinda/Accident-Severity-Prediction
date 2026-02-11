# 🚦 Road Accident Severity Prediction & Alert System

## 📌 Overview
This project is a **Machine Learning based Road Accident Severity Prediction System** integrated with a **Flask Web Application** and **SMS Alert Service**. The system predicts the severity of road accidents based on various factors such as driver details, vehicle details, road conditions, weather conditions, and speed limits.

If a potential accident risk is detected, the system sends an **alert SMS** with location details using Twilio.

---

## 🎯 Features
- 🚗 Predict accident severity using Machine Learning  
- 🌦️ Uses environmental and driver-related parameters  
- 📊 Statistical visualization of accident data  
- 📱 SMS alert system for accident warnings  
- 🌐 Interactive web interface using Flask  

---

## 🧠 Machine Learning Model
The project uses a **Random Forest Classifier** trained on real-world road safety datasets.

### Input Features
- Driver age  
- Vehicle type  
- Vehicle engine capacity  
- Day of the week  
- Weather condition  
- Road surface condition  
- Age of vehicle  
- Light condition  
- Driver gender  
- Speed limit  

### Output
- Predicted accident severity level  

---

## 🛠️ Tech Stack

### Backend
- Python  
- Flask  

### Machine Learning
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

### Other Integrations
- Twilio API (SMS alerts)
- Joblib (Model serialization)

---

## 📂 Project Structure

│── main.py # Flask application  
│── mlmodel.py # ML model training and evaluation  
│── mlp.sav # Saved trained model  
│── templates/  
│ ├── index.html  
│ ├── result.html  
│ ├── statistics.html  
│── DataSets/  
│ ├── Accident Dataset  
│ ├── Casualties Dataset  
│ ├── Vehicles Dataset  
