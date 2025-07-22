# ⚡ Hydroelectric Flow Prediction using Machine Learning

This project develops a comprehensive time series forecasting model to predict monthly flow rates in major Brazilian hydroelectric power plants. Using CatBoost regression with meteorological features and climate projections, the system generates both hydrological forecasts and Natural Affluent Energy (ENA) estimates for strategic energy sector planning.

---

## 📌 Overview

This project applies state-of-the-art machine learning techniques to support sustainable energy planning and climate risk assessment in Brazil's hydroelectric sector. By integrating historical hydrological data with meteorological variables and future climate projections (MIROC6), the model delivers accurate monthly flow predictions.

The pipeline is optimized for time series forecasting, incorporating domain-specific features, temporal validation, and rigorous performance evaluation to ensure reliable results for each hydroelectric facility.

---

## 🚀 Key Features

* **Modeling**: CatBoost Regressor (gradient boosting for tabular data)
* **Optimization**: Automated hyperparameter tuning with Optuna
* **Validation**: TimeSeriesSplit for time-aware cross-validation
* **Scope**: 19 hydroelectric power plants from diverse basins
* **Evaluation**: MAE, MSE, RMSE, R², and Adjusted R²
* **Forecasting**: Monthly predictions
* **Visualization**: Auto-generated plots for training, testing, and future results
* **ENA Calculation**: Flow-to-energy transformation using productivity coefficients

---


## 🧠 Methodology

1. **Preprocessing**: Time indexing, resampling, and feature scaling
2. **Feature Engineering**: Climate + temporal features (month/year)
3. **Model Training**: CatBoost with Optuna optimization (50 trials)
4. **Validation**: TimeSeriesSplit (4 folds) to ensure temporal integrity
5. **Evaluation**: Metrics calculated for both training and test sets
6. **Forecasting**: Monthly predictions from 2025 to 2050
7. **ENA Conversion**: Flow estimates converted to energy using plant-specific factors

---

## 🔍 Applications

* 🔌 Long-term energy planning
* 🌧 Climate risk analysis
* 📉 Flow variability monitoring
* ⚡ Grid operation & dispatch support

---

## 🤝 Contributing

Contributions are welcome! Please:

* Follow Python best practices
* Update documentation with changes
* Maintain code clarity and reproducibility

---

## 📜 License

Developed for research and educational purposes to support energy forecasting in the hydroelectric sector.

---

*This project demonstrates the use of modern machine learning techniques to support sustainable energy systems and climate-resilient infrastructure.*
