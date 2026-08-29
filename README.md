# ai-water-well-predictor
An AI-driven decision-support tool that predicts groundwater levels and classifies well-site risk using historical groundwater and climate data, without requiring physical sensors or IoT infrastructure.

Traditional well-site assessment relies on manual hydrogeological surveys — slow, resource-intensive, and often inaccessible in under-resourced regions. This project (SDG 9: Industry, Innovation, and Infrastructure) addresses that gap by learning from decades of multistation groundwater, rainfall, and temperature records to forecast groundwater levels and translate them into an actionable Safe / Declining / Critical risk category.

Pipeline: Data Source → Preprocessing → Model Training → Prediction → Risk Classification → Web Interface

Dataset: India Groundwater Climate Time-Series (Kaggle, 1994–2025)
Models: Random Forest Regressor, XGBoost (benchmarked against each other — no single model dominates this task per literature)
Evaluation: R², RMSE, MAE
Interface: Streamlit — input a region and time period, get a predicted groundwater level, risk category, and supporting visualizations (trend + feature importance)
Stack: Python, Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn, Streamlit
<img src="architecture_Diagram.png" alt="Alternative text" width="500">
