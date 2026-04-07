# linear-vs-polynomial-regression comparison Canada/Capita income 
Comparison of Linear and Polynomial Regression models to predict Canada’s per capita income and evaluate performance improvements.

inear vs Polynomial Regression

This project demonstrates the implementation and comparison of **Simple Linear Regression** and **Polynomial Regression** using Canada's Per Capita Income dataset.

The dataset contains:
- Year
- Per Capita Income (US$)

The goal is to predict income based on year and analyze model performance.

---
Models Used
1. Linear Regression
A simple model that assumes a straight-line relationship:

y = mx + b

Results:
- R² Score: **0.8909**
- MSE: **15,462,739**
- RMSE: **3932**

Interpretation:
- Explains ~89% of variance
- Good fit but fails to capture non-linear trends

---

2. Polynomial Regression (Degree = 2)
Enhances the model by adding a squared term:

y = b0 + b1(x) + b2(x²)

Results:
- R² Score: **0.9290**
- MSE: **10,056,378**
- RMSE: **3171**

Interpretation:
- Better fit than linear regression
- Captures curved growth pattern in data


Key Insights

- Income growth is **not perfectly linear**
- Polynomial regression improves accuracy
- Lower RMSE indicates better predictions
- Higher R² confirms better model fit

---

Conclusion

The Linear Regression model performs well but is limited by its assumption of linearity.
Polynomial Regression significantly improves performance by capturing non-linear trends in the data, making it a better choice for this dataset.


## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


---

⭐ If you like this project, give it a star!
