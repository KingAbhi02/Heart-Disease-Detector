# Heart-Disease-Detector
This project demonstrates an end-to-end machine learning workflow that merges predictions from two independent models:

Model 1: Coronary Artery Disease Prediction

Task: Binary classification (0 = No Disease, 1 = Disease)

Dataset: heartdisease.csv

Model 2: Arrhythmia Detection

Task: Multi-class classification (1–15 Arrhythmia types, where 1 = Normal)

Dataset: arrythmia.csv

The goal is to provide a single unified interface where users can upload patient datasets, run both models, and get combined predictions for comprehensive cardiac risk profiling.

✨ Features
✅ Upload two separate CSV files
✅ Predict disease presence and arrhythmia class
✅ Merge results into a unified output table
✅ Clean and user-friendly React frontend
✅ Modular Python backend (Flask) for easy integration of trained models

✨Technology used:

Frontend: React + Tailwind CSS

Backend: Python Flask

ML Libraries: scikit-learn, pandas, NumPy

Data Visualization: (Optional) Chart.js or matplotlib for extended insights
