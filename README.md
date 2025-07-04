# Concrete-strength-prediction
This project predicts the compressive strength of concrete using machine learning regression models. It demonstrates data cleaning, oversampling (SMOGN), model training, hyperparameter tuning, evaluation, and interpretability with SHAP.

## Project Goals
- Predict compressive strength (MPa) from mix design features
- Handle imbalance in high/low strength regions via SMOGN
- Compare multiple regression models
- Tune models for best performance
- Interpret model predictions

  ## 🧭 Notebook Structure
- **Setup & Imports**  
- **Load Data** from Excel with `openpyxl`  
- **Clean Columns** (remove newlines, strip spaces)  
- **EDA**: Distributions, Correlation Heatmaps  
- **Check Target Imbalance**  
- **SMOGN Oversampling** to balance target distribution  
- **Visualization** of before/after oversampling  
- **Split Features & Target**  
- **Scale Features** with StandardScaler  
- **Train-Test Split**  
- **Define and Expand Model Types**  
- **Hyperparameter Tuning** with GridSearchCV  
- **Evaluate** with MAE, RMSE, R²  
- **Residual and Actual vs Predicted Plots**  
- **Ensemble Models** (Stacking, Voting)  
- **Interpretability with SHAP**  
- **Save Best Model**

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


## 📈 Example Outputs
- Target distribution plots before and after SMOGN
- Residual plots
- Actual vs Predicted scatter plots
- SHAP summary plots


## ✅ Requirements
All dependencies are listed in `requirements.txt`. Example:

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

