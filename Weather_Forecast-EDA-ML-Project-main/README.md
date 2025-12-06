# 🌦️ Weather Forecasting & Rain Prediction using Machine Learning & Time-Series Modeling

This project focuses on **collecting live weather data**, performing **exploratory data analysis (EDA)**, and building multiple **machine learning models** and **time-series forecasting models** to predict:

- 🌧️ **Rain prediction (classification)**
- 🌡️ **Temperature forecasting (regression & time-series)**
- 📈 **City-wise weather pattern analysis**

The data is fetched from **WeatherAPI.com** and processed in **Jupyter Notebook**.

---

## 🚀 Project Features

### ✔ 1. Live Weather Data Collection  
- Fetch hourly historical weather data  
- Multiple cities support  
- Auto data cleaning & merging  
- Saves dataset as CSV  

### ✔ 2. Exploratory Data Analysis (EDA)  
- Temperature trends  
- Humidity / wind / rainfall analysis  
- City-wise comparisons  
- Correlation matrix  
- Time-based features (hour, day, month, weekday)

### ✔ 3. Feature Engineering  
- Lag features  
- Rolling averages  
- Rain_next_hour label  
- Time features  
- City one-hot encoding  

### ✔ 4. Machine Learning Models  
#### Rain Prediction (Classification)
- RandomForestClassifier  
- Balanced class weights  
- ROC, Accuracy, Precision, Recall  

#### Temperature Forecasting (Regression)
- RandomForestRegressor  
- Prophet (Time-series forecasting)  

### ✔ 5. Time-Series Forecasting (Prophet)  
- Hourly forecasting  
- Multi-seasonality (daily, weekly, yearly)  
- Optional regressors (humidity)  
- Forecast visualization  

### ✔ 6. Dashboard (Plotly)  
- Interactive temperature charts  
- Rain probability graphs  
- City-wise comparison dashboard  

---

## 📂 Project Structure

```weather-ml-project/
│
├── data/
│ └── weatherapi.com
│
├── models/
│ ├── rain_rf_model.joblib
│ └── temp_forecast_prophet/
│
├── notebooks/
│ └── weather_ml_project.ipynb
│
├── README.md
└── requirements.txt
```


---

## ⚙️ Installation & Setup

### 1️⃣ Clone this repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```
### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Add your API Key
Get a free key from: https://www.weatherapi.com
API_KEY = "YOUR_OWN_API_KEY"

Enter city names (comma separated): Delhi, Mumbai, Chennai
How many past days do you want? 60

---

## 👨‍💻 Author
**Mohammed Hayath RK**  

**Skills**
- Machine Learning (Classification & Regression)
- Data Preprocessing & Feature Engineering
- Time‑Series Forecasting (Prophet)
- Model Evaluation & Optimization
- GitHub Project Structuring

**Contributions**
- Built RandomForest Rain Prediction Model  
- Developed Temperature Forecasting Pipeline  
- Implemented Time‑Series models with Prophet  
- Performed EDA & Feature Engineering  
