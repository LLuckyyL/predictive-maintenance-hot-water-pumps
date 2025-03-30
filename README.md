# Predictive Maintenance for Hot Water Pumps

This project builds a machine learning model to predict potential faults in residential hot water pumps using simulated sensor data and environmental conditions.

## 🔍 Problem Statement
Hot water pumps can experience stress and failure due to environmental factors like temperature and humidity, as well as irregular usage patterns. Predicting potential faults helps prevent breakdowns and reduces maintenance costs.

## 🧰 Tools & Technologies
- Python, pandas, scikit-learn
- Random Forest Classifier
- Feature Engineering
- Jupyter Notebook

## 📊 Features Created
- **Ambient Stress**: Stress caused by temperatures above optimal operating range.
- **Usage Anomaly**: Absolute deviation from the average flow rate, indicating unusual usage behavior.

## 📁 Files
- `Predictive_Maintenance_Hot_Water_Pumps.ipynb`: Full analysis and model training notebook.
- `hot_water_pump_data.csv`: Simulated dataset with timestamps, weather, usage, and fault risk.

## ✅ Model Performance
The Random Forest model identifies fault risks using engineered features and performs well on the test set. Evaluation includes accuracy, precision, recall, and F1-score.

## 📌 Author
[Lakindu Perera](https://www.linkedin.com/in/lokuwattage-perera-29087a226/)
