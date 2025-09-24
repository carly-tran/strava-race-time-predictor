# Strava Race Time Predictor

This project uses Strava training data and machine learning to predict half-marathon (and other races) finish times. By combining training load, long-run paces, heart-rate zones, elevation gain, and other workout features, the model provides a data-driven estimate of race performance.

## Overview
- Uses training features such as pace, heart rate zones, elevation, and mileage.
- Includes feature engineering, exploratory data analysis, and regression-based models.
- Provides visualizations of training load, predicted finish times, and actual vs. predicted comparisons.
- Raw Strava exports are excluded for privacy.

## Features
- Data cleaning pipeline for Strava exports.
- Feature engineering: rolling averages, long-run effects, heart rate distribution.
- Modeling: linear regression, ridge regression, random forest.
- Visualization of trends and model performance.
- Reproducibility with `requirements.txt` and `.env.example`.
