# Weather Intelligence System 🌦️

## Project Overview

The Weather Intelligence System is a data engineering and machine learning project that collects real-time weather data from multiple cities using a Weather API, performs ETL (Extract, Transform, Load) operations, stores the cleaned data in SQLite, visualizes weather trends, and predicts humidity using Machine Learning.

This project demonstrates the complete workflow of:

* API Integration
* Data Cleaning & Transformation
* SQL Database Handling
* Data Visualization
* Machine Learning Prediction

---

# Features

✅ Real-time weather data collection using API
✅ ETL pipeline for data cleaning
✅ Missing value handling
✅ Duplicate removal
✅ Heat Index calculation
✅ SQLite database storage
✅ SQL querying and analytics
✅ Weather data visualization
✅ Humidity prediction using Linear Regression
✅ GitHub-ready project structure

---

# Technologies Used

* Python
* Pandas
* Requests
* SQLite3
* Matplotlib
* Seaborn
* Scikit-learn

---

# API Used

OpenWeatherMap API

---

# Cities Included

* Chennai
* Mumbai
* Delhi
* Bengaluru

---

# Project Workflow

## 1. Data Collection

Weather data is collected using the OpenWeatherMap API for multiple cities.

## 2. ETL Process

The collected data is:

* cleaned
* validated
* transformed
* checked for missing values
* checked for duplicate records

## 3. Feature Engineering

A new column called `heat_index` is created using temperature and humidity.

## 4. Database Storage

The cleaned dataset is stored in SQLite database tables.

## 5. Data Visualization

Charts and graphs are created to analyze:

* Temperature
* Humidity
* Weather Conditions
* Correlation between variables

## 6. Machine Learning

A Linear Regression model is trained to predict humidity using:

* temperature
* pressure
* wind speed

---

# Sample Visualizations

* Temperature Bar Chart
* Humidity Line Chart
* Weather Condition Pie Chart
* Correlation Heatmap

---

# Machine Learning Model

Model Used:

* Linear Regression

Evaluation Metric:

* Mean Absolute Error (MAE)

---

# Project Structure

```bash
Weather-Intelligence-System/
│
├── weather_project.ipynb
├── weather_data.csv
├── weather_database.db
├── README.md
└── requirements.txt
```

---

# How to Run the Project

## Step 1

Clone the repository

```bash
git clone <repository_link>
```

## Step 2

Install required libraries

```bash
pip install pandas requests matplotlib seaborn scikit-learn sqlalchemy
```

## Step 3

Run the notebook or Python script

---

# Future Enhancements

* Real-time dashboard
* Weather forecasting
* Rain prediction
* Streamlit web application
* Power BI dashboard integration
* Advanced ML models

---

# Conclusion

This project demonstrates a complete end-to-end weather analytics pipeline integrating APIs, ETL, SQL, Visualization, and Machine Learning in Python.

---

# Author

Rithanya

