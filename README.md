# ML-Projects
Welcome! This folder contains all my ML-projects. Below are brief descriptions and links to the corresponding folders.

## 1) Housing Price Predictor
<img width="1429" height="756" alt="458637868-a3fec453-b305-4725-b909-b17fa7b4cb49" src="https://github.com/user-attachments/assets/208b95c9-d474-464f-85c5-917208679b92" />

A **production-ready ML application** for real estate price prediction using **XGBoost**, interpretability (SHAP/LIME), and a **Streamlit web interface**. The project demonstrates the full cycle: data generation/preparation, training with hyperparameter tuning (Optuna), artifact persistence, dashboards, error handling, and a modular architecture. Supports **EN/RU** interface switching.

**Key Features**
- XGBoost + Optuna (10k+ records, automated training)
- Streamlit UI: real-time predictions, data analysis, visualizations
- Interpretability: **SHAP** (feature importance), **LIME** (local behavior)
- Advanced preprocessing: features for location/infrastructure/environment, outlier handling (IQR)
- Metrics: R², RMSE, MAE, MAPE + plots
- Logging, robustness to missing values, structured persistence of models/configs

**Technologies**: Python 3.8+, `xgboost`, `streamlit`, `shap`, `optuna`, `plotly`

**Structure (main)**
- `app.py` — web interface (EN/RU)
- `train_model.py` — automated training & optimization
- `config/config.py` — data/model parameters
- `src/model.py` — XGBoost wrapper (fit/predict/eval)
- `src/data_processing.py` — preprocessing & feature engineering
- `src/visualization.py` — plots & dashboards
- `src/explainer.py` — SHAP/LIME

<a href="https://github.com/NicolasPetrov/Housing-Price-Predictor"><kbd>Learn more →</kbd></a>

---
