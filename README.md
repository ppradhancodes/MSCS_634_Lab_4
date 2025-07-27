# Lab 4 – Regression Modeling and Regularization  
**Course:** MSCS 634 – Big Data and Data Mining  
**Dataset:** Diabetes Dataset from `sklearn.datasets`  

## Purpose
The purpose of this lab was to apply and evaluate various regression techniques to predict disease progression in diabetes patients using real-world medical data. Specifically, we implemented and compared:
- Simple Linear Regression  
- Multiple Linear Regression  
- Polynomial Regression  
- Ridge Regression  
- Lasso Regression  

We also explored how regularization techniques like Ridge and Lasso help address overfitting and improve model generalization.

## Key Insights
- **Multiple Linear Regression** performed better than Simple Linear Regression, showing the value of using multiple features to capture complex relationships in the data.
- **Ridge Regression** offered the best balance of accuracy and stability, slightly improving performance by penalizing large coefficients.
- **Lasso Regression** added interpretability by shrinking less relevant features to zero, acting as a form of feature selection.
- **Polynomial Regression** with higher degrees increased model complexity but introduced overfitting, highlighting the need for regularization.
- **BMI** emerged as the most predictive single feature in the dataset.

## Challenges and Decisions
- Selecting the right degree for Polynomial Regression required balancing model accuracy with overfitting risk.
- Choosing appropriate alpha values for Ridge and Lasso involved experimentation, as too small or large values led to underfitting or overfitting.
- Interpreting model outputs and deciding how to fairly compare models required consistent evaluation using MAE, MSE, RMSE, and R².

## Files Included
- `Lab4_Regression.ipynb`: Jupyter Notebook with full code, models, visualizations, and evaluation.
- `README.md`: This file.

## Notes
- All models were trained and tested on the same train/test split for consistency.
- Visualizations were included to compare actual vs. predicted values and assess model fit.
