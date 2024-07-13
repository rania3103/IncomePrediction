# 💰💵💸I̳n̳c̳o̳m̳e̳ ̳P̳r̳e̳d̳i̳c̳t̳i̳o̳n̳🔍🤔📉

<img src="img.jpg">

## Overview 🔍
This project focuses on predicting household income using machine learning techniques. The goal is to build a regression model that accurately predicts household income based on various factors.

## Dataset 🗂️
- The dataset contains information on demographic variables such as `age`, `number of dependents`, `work experience`, `household size`, `location`, `homeownership status`, `primary mode of transportation`, `employment status`, `marital status`, `type of housing`, and `income`.
- Target Variable: `Income_Log` (log-transformed using `log1p` for improved model performance)

The dataset used can be found on Kaggle [here](https://www.kaggle.com/datasets/stealthtechnologies/regression-dataset-for-household-income-analysis).

## Tools Used 🛠️
<p>  
  <img alt="Python" src="https://img.shields.io/badge/python-306998.svg?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white"/>
  <img alt="Scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img alt="Seaborn" src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=Seaborn&logoColor=white"/>
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img alt="SciPy" src="https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white"/>
</p>

- **Pandas:** Data manipulation and analysis.
- **Seaborn:** Statistical data visualization.
- **Matplotlib:** Plotting library for Python.
- **Scikit_learn:** Machine learning library for Python.
- **numpy:** Fundamental package for scientific computing with Python.
- **scipy:** Library for scientific and technical computing, including optimization, linear algebra, and statistics.

## Project Workflow 🎯
1. **Data Preprocessing:**
   - Numerical features are scaled using `StandardScaler`.
   - Categorical features are one-hot encoded using `OneHotEncoder`.
   - Target variable (Income_Log) is log-transformed to handle skewness.
2. **Model Selection:**
   - Evaluated models: Linear Regression, Decision Tree, Random Forest, Support Vector Machine (SVR), Gradient Boosting, XGBoost, CatBoost, LightGBM.
   - Models are evaluated based on Mean Squared Error (MSE).

3. **Hyperparameter Tuning:**
   - Optimized Random Forest, CatBoost, and LightGBM models using RandomizedSearchCV to find the best hyperparameters.

4. **Stacking Ensemble:**
   - Combined predictions from optimized models using a StackingRegressor with a final estimator of Linear Regression.

5. **Model Evaluation:**
   - Evaluated the final stacking model using MSE ,RMSE to ensure robustness.

6. **Feature Importance:**
   - Analyzed feature importances to understand which factors (work experience, age) most influence household income prediction.

## Findings✨🕵
- Feature importance analysis revealed that work experience and age were the most influential factors in predicting household income.

## 👩‍💻 Author

- GitHub: [@rania3103](https://github.com/rania3103)
- LinkedIn: [LinkedIn](https://linkedin.com/in/rania-abassi-24105a249)
