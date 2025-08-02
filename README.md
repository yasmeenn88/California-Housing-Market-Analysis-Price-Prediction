# 🏠 California Housing Market Analysis & Price Prediction

This project explores and models California housing data using multiple regression techniques to predict house prices. It includes data cleaning, visualization, feature engineering, and evaluation of several models, selecting the best one based on performance metrics.

---

## 📂 Dataset

- **Source:** [Kaggle - California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- **Description:** This dataset contains information about California districts, including median house value, income levels, proximity to the ocean, and housing characteristics.

---

##  Project Goals

- Analyze relationships between housing features and price.
- Visualize geospatial trends and feature correlations.
- Train and compare multiple regression models.
- Evaluate models using RMSE, MAE, MSE, and R² score.
- Select and save the best-performing model for deployment.

---

##  Models Used

| Model               | Description                        |
|--------------------|------------------------------------|
| Linear Regression  | Baseline linear model              |
| Ridge Regression   | L2 regularization                  |
| Lasso Regression   | L1 regularization                  |
| Random Forest      | Ensemble tree-based model          |
| Gradient Boosting  | Boosted tree ensemble              |


---

## 📈 Sample Results

| Model              | R² Score |
|-------------------|----------|
| Random Forest      | 0.8165   |
| Gradient Boosting  | 0.7617   |
| Ridge Regression   | 0.6255   |
| Lasso Regression   | 0.6254   |
| Linear Regression  | 0.6254   |

>  **Best Model:** Random Forest

---
 **All modeling, visualizations, and evaluation were done in a Jupyter Notebook `california housing prices.ipynb`.**


