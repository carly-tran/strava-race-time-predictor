# 🏃 Strava Race Time Predictor

Predict half-marathon (and other races) finish times using **training data from Strava** combined with machine learning models.  
This project is both a **portfolio piece** (clear, documented, reproducible) and a **practical tool** for analyzing running performance.

---

## 📌 Overview
- Uses training data (pace, heart rate zones, elevation, mileage) to predict likely race finish times.  
- Implements **feature engineering**, **exploratory data analysis**, and **ML models** (e.g. regression, tree-based).  
- Visualizes training load vs. predicted time with **Jupyter notebooks & plots**.  
- Designed with reproducibility and data privacy in mind — **no raw Strava exports are included**.

---

## ⚡ Key Features
- **Data pipeline**: Cleans Strava exports into structured CSV/Parquet.  
- **Feature engineering**: Rolling averages, long-run effects, heart-rate zone distribution.  
- **Modeling**: Regression baselines, ML models (e.g. Ridge/Random Forest).  
- **Visualization**: Training progress, predicted finish time distributions, actual vs. predicted plots.  
- **Reproducibility**: `requirements.txt` + `.env.example` for API keys and configs.  
