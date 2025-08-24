Aircraft Engine RUL Prediction

📌 Overview


This project focuses on predicting the Remaining Useful Life (RUL) of aircraft engines using the CMAPSS dataset (FD001) provided by NASA. Accurate RUL prediction is a key challenge in predictive maintenance, helping reduce unexpected failures, downtime, and costs in aerospace systems.


We implemented multiple models — Random Forest Regression, XGBoost, Gated Recurrent Unit (GRU), and Long Short-Term Memory (LSTM) — and compared their performance using Root Mean Square Error (RMSE).


⚙️ Methodology
Dataset Preprocessing

Loaded CMAPSS FD001 dataset.

Extracted sensor readings and operational settings.

Generated RUL labels for supervised learning.

Normalized data for deep learning models.

Models Implemented

Random Forest Regression (RF) – baseline traditional ML model.

XGBoost – gradient boosting approach for structured data.

GRU (Gated Recurrent Unit) – recurrent model for time-series.

LSTM (Long Short-Term Memory) – deep sequence model for long-term dependencies.


Evaluation

Used RMSE as the performance metric.

Compared results across models to identify the best-performing approach.

📊 Results


Traditional ML (RF, XGBoost) provided baseline performance.

Deep learning models (GRU, LSTM) captured temporal dependencies more effectively, achieving lower RMSE.

LSTM achieved the most promising results for long-term RUL prediction.


