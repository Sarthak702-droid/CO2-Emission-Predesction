# 🚗 CO₂ Emissions Prediction

This project explores different **Machine Learning models** to predict **CO₂ emissions** based on vehicle features. We experiment with both **linear** and **non-linear models** and compare their performance using metrics like **MSE, MAE, and $R^2$**.

***

## 📌 Project Overview
- Analyze the CO₂ emissions dataset.
- Apply and compare different regression models.
- Visualize predicted vs. actual emissions.
- Evaluate models using standard error metrics.

***

## ⚙️ Models Implemented
1.  **Linear Regression** – Simple baseline model.
2.  **Polynomial Regression** – Captures non-linear patterns.
3.  **Ridge Regression** – Regularized linear model to prevent overfitting.
4.  **Lasso Regression** – Regularized model with feature selection.
5.  **Decision Tree Regression** – Tree-based model that handles non-linear data.
6.  **Random Forest Regression** – Ensemble of decision trees for better accuracy.

***

## 📊 Evaluation Metrics
-   **MSE (Mean Squared Error)**: Measures the average of the squares of the errors.
-   **MAE (Mean Absolute Error)**: Measures the average magnitude of the errors in a set of predictions.
-   **$R^2$ Score (Coefficient of Determination)**: Indicates the proportion of the variance in the dependent variable that is predictable from the independent variable(s).

***

## 📈 Results Comparison

The performance of the key models is summarized below. The Decision Tree model demonstrated the best performance with the lowest error rates and the highest $R^2$ score.

| Model | MSE | MAE | $R^2$ |
| :--- | :---: | :---: | :---: |
| Linear Regression | 38.04 | 3.62 | 0.9895 |
| Ridge Regression | 32.75 | 3.16 | 0.9909 |
| Lasso Regression | 41.42 | 3.75 | 0.9885 |
| **Decision Tree Regression** | **26.69** | **2.44** | **0.9926** |

> 🔑 **Best Model:** **Decision Tree Regression** achieved the lowest errors and the highest $R^2$ score.

***

## 🔍 Visualizations
The scatter plots below illustrate the performance of each model by comparing the **predicted CO₂ emissions** against the **actual values**. A perfect prediction would have all points lying exactly on the dashed red line. As shown, all models perform very well, with the points tightly clustered around the line, visually confirming the high $R^2$ scores.



***

## 🚀 How to Run
1.  Open the notebook in Google Colab:
    👉 [See Preview](https://colab.research.google.com/drive/1MpXxAMtXzBq280qNaYdI_zvmm0sOuFxS#scrollTo=8039fc5a)
2.  Upload the dataset (`co2.csv`).
3.  Run all cells to train and evaluate the models.

***

## 📂 Dataset
The dataset includes vehicle features like:
-   Engine size
-   Cylinders
-   Fuel consumption
-   CO₂ emissions

***

## 🛠️ Requirements
-   Python 3.x
-   Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

***

## 🎯 Learning Outcomes
-   Understand and compare regression models.
-   Learn the effect of regularization (Ridge, Lasso).
-   Explore tree-based methods (Decision Tree, Random Forest).
-   Evaluate models using error metrics.

---
✍️ *Author: [Sarthak Tripathy]*
📌 *Machine Learning | Regression Models | CO₂ Prediction*
