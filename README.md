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

# 📊 Visualizations
1. Battery Cycle Parameters
We plotted measured voltage, current, temperature, and charge/discharge behaviors during one cycle to understand the raw data.
<img width="726" height="446" alt="image" src="https://github.com/user-attachments/assets/ce668b22-8d58-4fbc-9775-6d09afdbc9d1" />

# 2. Model Performance – MSE Comparison
Compared the Mean Squared Error (MSE) of Ridge, Random Forest, and XGBoost.
<img width="575" height="399" alt="image" src="https://github.com/user-attachments/assets/917930f5-5bc4-4520-b387-2bf66ee7e293" />

# 3. Model Performance – R² Score

Evaluated how well each model explains variance in RUL predictions using the R² score.

<img width="524" height="398" alt="image" src="https://github.com/user-attachments/assets/5b2d6eea-be08-4cd6-9e44-fa0bace49026" />)

# 4. Predicted vs Actual RUL

Scatter plots were generated to compare true RUL values vs model predictions for all three models. This helps visualize accuracy and bias.
<img width="770" height="416" alt="image" src="https://github.com/user-attachments/assets/9f904f21-7466-4c5a-8b1c-feee27765785" />


# Feature Importance given by the model trained with XGBoost
<img width="630" height="362" alt="image" src="https://github.com/user-attachments/assets/724f1276-ae4d-4ebc-9024-7a8e1c310e01" />
