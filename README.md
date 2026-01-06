📘 Internship Daily Diary
Smart Farm Hybrid Weather & Crop Yield Prediction System

Organization: REQServe
Intern: Karamveer kaur 
Duration: July 2025 – December 2025
Smart Farm Hybrid Weather & Crop Yield Prediction System

A comprehensive agricultural intelligence platform developed during a 6-month internship at REQServe, focused on integrating real-time weather data, machine learning-based crop yield prediction, and decision support tools to assist farmers, planners, and agronomists.

📌 Project Overview

Agriculture is highly sensitive to weather variability and climate conditions. Traditional forecasting methods often lack accuracy and actionable insights at the local level.
This project addresses these challenges by combining live weather intelligence, historical climate analytics, and machine learning models to provide reliable crop yield predictions and risk-aware recommendations.

The system is implemented as an interactive Streamlit web application with multiple analytical and advisory modules.

🚀 Key Features

🌦 Live Weather Intelligence

Real-time data using OpenWeather API

Temperature, rainfall, humidity, cloud cover, and weather summaries

📊 Crop Yield Prediction

Machine Learning models:

Random Forest Regressor (Best Model)

Gradient Boosting Regressor

Linear Regression

Evaluation Metrics:

R² Score ≈ 0.94

RMSE ≈ 0.65 tons/ha

MAE ≈ 0.48 tons/ha

📈 Climate Analytics

Seasonal weather trends

Rainfall and temperature analysis

Historical vs predicted comparisons

⚠️ Risk Alert System

Temperature threshold alerts

Rainfall deficit warnings

Weather-based risk identification

🌱 Advanced Agricultural Modules

Multi-crop recommendation system

Seasonal planning calendar

Cost–benefit analysis

Disease alert system

Knowledge base for crops and schemes

AI-powered Agri Expert chatbot (Google Gemini)

📄 Export & Reporting

PDF report generation

Excel data export

🧠 Technology Stack
Machine Learning

Scikit-learn

Random Forest

Gradient Boosting

Linear Regression

XGBoost

Joblib

Data Processing & Visualization

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Plotly

Web & API

Streamlit

OpenWeather API

Requests

Google Generative AI (Gemini)

Reporting

ReportLab (PDF)

OpenPyXL (Excel)

🗂 Project Structure
predictive-weather-analytics/
├── streamlit_app/
│   ├── streamlit_app.py
│   ├── pages/
│   └── utils/
├── data/
├── models/
├── raw_dataset/
├── processed_dataset/
├── presentation_assets/
├── processing.ipynb
├── process.ipynb
├── requirements.txt
├── DAILY_DIARY.md
└── README.md

📊 Dataset Information

Source: Synthetic dataset (1M+ records)

Features:

Soil Type

Crop Type

Rainfall (mm)

Temperature (°C)

Fertilizer Usage

Irrigation Usage

Weather Condition

Target Variable: Crop Yield (tons/hectare)

⚙️ Installation & Setup
git clone https://github.com/karam-2003/predictive-weather-analytics.git
cd predictive-weather-analytics
pip install -r requirements.txt


Create .streamlit/secrets.toml:

OPENWEATHER_API_KEY = "your_api_key_here"


Run the application:

streamlit run streamlit_app/streamlit_app.py

📘 Internship Daily Diary

A complete 6-month daily internship diary documenting:

Learning objectives

Development milestones

Model building

API integration

Dashboard implementation

Final submission

📄 File: DAILY_DIARY.md
