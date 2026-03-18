# Predictive Maintenance using ESP32 and Machine Learning

## Overview
This project uses vibration data from MPU6050 sensor to detect abnormal machine behavior using machine learning.

## Pipeline
Sensor Data → Windowing → Feature Extraction → ML Model → Prediction

## Features
- Mean
- Standard Deviation
- Variance
- RMS
- Max
- Min

## Models
- Logistic Regression (~88%)
- Random Forest (100%)

## Results
Random Forest outperformed Logistic Regression by capturing non-linear patterns in vibration data.

## Future Work
- Real time prediction using ESP32
- Integration with additional sensors
