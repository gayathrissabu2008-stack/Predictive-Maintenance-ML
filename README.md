# Predictive-Maintenance-Machine Learning
The objective of this project is to develop an AI/ML-based predictive maintenance system that analyzes machine operating parameters such as temperature, rotational speed, torque, and tool wear to predict whether a machine is likely to fail.

## Overview

This project predicts machine failures using machine sensor data from the AI4I 2020 Predictive Maintenance Dataset.

The goal is to identify potential machine failures before they occur by analyzing operating conditions such as temperature, rotational speed, torque, and tool wear.

---

## Dataset

Dataset: AI4I 2020 Predictive Maintenance Dataset

Number of records: 10,000

Target Variable:
- Machine failure (0 = Healthy, 1 = Failure)

Features Used:
- Air temperature [K]
- Process temperature [K]
- Rotational speed [rpm]
- Torque [Nm]
- Tool wear [min]

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Joblib

---

## Workflow

1. Load dataset
2. Clean unnecessary columns
3. Perform exploratory data analysis
4. Split data into training and testing sets
5. Train multiple machine learning models
6. Compare model performance
7. Analyze feature importance
8. Save trained model
9. Predict machine failures

---

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest

---

## Results

- Random Forest Accuracy: 98.35%
- Decision Tree Accuracy: 97.90%
- Logistic Regression Accuracy: 97.00%

Key Finding:
- Torque was the most important feature for predicting machine failures.

---

## Future Improvements

- Real-time sensor integration
- IoT-based predictive maintenance system
- Web dashboard for monitoring machine health
- Deep learning models for failure prediction
## Author

Gayathri S