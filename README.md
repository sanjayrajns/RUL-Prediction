# 🔋 Battery Remaining Useful Life (RUL) Prediction

This project predicts the Remaining Useful Life (RUL) of lithium-ion batteries using machine learning models such as Ridge Regression, Random Forest, and XGBoost. It uses NASA’s Battery Dataset and extracts features like voltage, current, temperature, and internal resistance (Re, Rct) to estimate battery health over charge/discharge cycles.

An interactive Streamlit app is included so users can input battery parameters and instantly get RUL predictions.

# 🚀 Features

Extracts features from raw NASA battery cycling data.

Implements multiple ML models:

Ridge Regression (Baseline)

Random Forest Regressor

XGBoost Regressor (best performer)

Model comparison with MSE and R² plots.
