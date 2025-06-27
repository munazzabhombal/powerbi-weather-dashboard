# 🌦️ Real-Time Weather & AQI Dashboard – Power BI Project

This Power BI dashboard provides **real-time weather and air quality data** for multiple cities using live API integration. It offers an intuitive and interactive UI that displays key weather metrics, AQI levels, and environmental trends in a clean, dark-themed design.

![weather-dashboard-1](https://github.com/user-attachments/assets/91ee22ff-21c1-443f-a28a-16db14b7fb85)

---

## 🚀 Features
- 🔄 **Real-time data fetching** using public weather and AQI APIs  
- 🌇 **Multi-city support** (Mumbai, Pune, Lucknow)  
- 📊 Visuals include:  
  - Temperature, Humidity, Wind, Pressure, Visibility (Cards & KPIs)  
  - Air Quality Indicators (CO, NO2, SO2, PM2.5, PM10, O3)  
  - Sunrise/Sunset times, UV Index, Rain Probability  
  - Line & Bar Charts for trends  
  - Conditional formatting for AQI zones  
- 📱 Mobile-friendly layout  
- 🌌 Dark theme for better UX  

---

## 🧠 Technical Highlights

### 🔗 Data Integration
- API calls for live data ingestion  
- Separate queries for each city using **duplicate tables and references**

### 🔧 Data Transformation
- Cleaned and reshaped using **Power Query Editor**  
- Converted and formatted metrics (e.g., visibility, temperature, AQI interpretation)

### 🧩 Data Modeling
- Used **Galaxy Schema** with clear fact-dimension separation  
- Handled **many-to-many relationships** using bridging tables to resolve ambiguity

### 🧮 DAX Measures
Created custom DAX measures and columns using:
- `SELECTEDVALUE`, `FIRSTNONBLANK`, `FORMAT`  
- Defined **variables** (`VAR`) for cleaner and reusable logic  
- Used **`SWITCH(TRUE(), ...)`** for AQI categories, conditional logic, and dynamic labeling  

---

## 📌 Future Enhancements
- Auto-refresh via Power BI Service  
- Add more cities dynamically  

---

## 📬 Feedback
Feel free to open issues or drop suggestions!  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/munazzabhombal/) 🚀
