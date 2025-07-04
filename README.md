# Concrete-strength-prediction
This project predicts the compressive strength of concrete using machine learning regression models. It demonstrates data cleaning, oversampling (SMOGN), model training, hyperparameter tuning, evaluation, and interpretability with SHAP.
## Project Goals
- Predict compressive strength (MPa) from mix design features
- Handle imbalance in high/low strength regions via SMOGN
- Compare multiple regression models
- Tune models for best performance
- Interpret model predictions

## 🛠️ Features
- Data loading from Excel
- Column cleaning
- Target distribution visualization
- SMOGN oversampling
- Model training (linear, tree, ensemble, neural nets)
- Hyperparameter tuning with GridSearchCV
- Evaluation metrics (RMSE, MAE, R2)
- Residual and actual-vs-predicted plots
- SHAP interpretability

## 🚀 How to Run
1. Clone the repo
2. Install dependencies:
4. Follow the notebook cells.

## 📈 Results
- Best model performance on test set
- Improved prediction in rare/high-strength regions via SMOGN
- Feature importances via SHAP plots

## 📜 License
MIT

