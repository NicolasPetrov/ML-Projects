# ML-Projects
Welcome! This folder contains all my ML-projects. Below are brief descriptions and links to the corresponding folders.

## 1) Housing Price Predictor
<img width="1432" height="672" alt="screen" src="https://github.com/user-attachments/assets/0668f90b-cfef-42d2-a4c2-73032dd8755b" />

**Housing Price Predictor** is an advanced machine learning system for predicting real estate prices using XGBoost with comprehensive factor analysis. Built with a web interface powered by Streamlit, this application provides highly accurate price predictions with detailed model explanations and interactive visualizations using **41 comprehensive factors** instead of basic property characteristics.

This project serves as an example of building a production-ready machine learning application with advanced feature engineering, comprehensive environmental and social factor analysis, and extensive real estate market modeling.

#### Technical Details
- **Language**: Python 3.8+
- **Main Libraries**:
  - `xgboost`: Advanced gradient boosting algorithm for 41-factor price prediction.
  - `streamlit`: Web application framework with tabbed interface for complex factor input.
  - `shap`: Model interpretability for environmental, social, and infrastructure factor analysis.
  - `optuna`: Hyperparameter optimization for multi-factor model tuning.
  - `plotly`: Interactive visualizations for comprehensive factor analysis and quality scoring.
  - `pytest`: Comprehensive testing framework covering all 41 factors.
- **Architecture**:
  - **Advanced Interface Design**: Comprehensive 41-factor analysis system
  - **Quality Scoring System**: Environmental, Infrastructure, and Building quality indices
- **Structure**:
  - `app.py`: Advanced Streamlit application with full 41-factor control and tabbed organization.
  - `train_model.py`: Automated model training with 41-factor data generation and comprehensive validation.
  - `config/config.py`: Environment-based configuration with factor weight management.
  - `src/model.py`: XGBoost model implementation with 41-factor support and comprehensive error handling.
  - `src/data_processing.py`: Advanced data preprocessing with environmental, social, and infrastructure factor engineering.
  - `src/visualization.py`: Enhanced plotting utilities for multi-factor analysis and quality scoring visualization.
  - `src/explainer.py`: SHAP model explanations for complex factor interactions and importance analysis.
  - `src/data_validators.py`: Comprehensive validation for all 41 factors with real estate market logic.
  - `src/exceptions.py`: Custom exception hierarchy for advanced real estate data handling.
  - `tests/`: Complete test suite with 41-factor validation and market logic testing.

<a href="https://github.com/NicolasPetrov/Housing-Price-Predictor"><kbd>Learn more →</kbd></a>

---
