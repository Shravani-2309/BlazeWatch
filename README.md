# BlazeWatch: Forest Fire Prediction System

## 📌 Project Overview
**BlazeWatch** is a machine learning-based forest fire prediction system that uses **historical datasets** to predict the likelihood of a fire based on three environmental parameters:
- Temperature
- Humidity
- Oxygen level

Unlike traditional methods that rely on **IoT sensors**, **satellites**, or **real-time weather feeds**, BlazeWatch works entirely on **past fire data**, making it **affordable, scalable, and accessible** — even in low-resource regions.

---

##  Problem Statement
Forest fires are increasing due to climate change and human activity.  
Existing systems like **satellite monitoring**, **drones**, and **weather-based indices** are:
- Costly to set up and maintain
- Dependent on weather conditions
- Slow to provide updates
- Not adaptable to local patterns

**BlazeWatch solves this** by using **machine learning on historical data** to predict fire occurrence **before it happens**.

---

## 💡 Proposed Solution
BlazeWatch predicts fire occurrence using:
- **Random Forest**, **SVM**, and other ML models
- Inputs: Temperature, Humidity, Oxygen
- Outputs: Fire Occurred / Fire Did Not Occur + Forest Name, City, State, Region


---

## 🛠️ Project Modules
1. **Dataset Input Module** – Loads historical fire dataset.
2. **Data Preprocessing Module** – Cleans, normalizes, and prepares data.
3. **ML Prediction Engine** – Predicts fire occurrence based on inputs.
4. **Dashboard Interface** – User-friendly web app for interaction.
5. **Insights & Alerts Module** – Displays results and forest details.

---

## 📌 Future Scope
- Add more inputs like wind speed, rainfall, vegetation type
- Develop a mobile app for forest officers
- Integrate deep learning models for better accuracy
- Include interactive fire risk maps
- Multilingual interface for wider adoption

---


## 📜 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BlazeWatch.git
   cd BlazeWatch
2.Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3.Run the Flask app:
   ```bash
    python app.py
   ```
4.Open your browser and go to:
   ```bash
     http://127.0.0.1:5000
   ```


