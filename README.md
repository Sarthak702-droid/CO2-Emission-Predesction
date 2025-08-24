# 🚗 CO₂ Emissions Prediction

This project explores different **Machine Learning models** to predict **CO₂ emissions** based on vehicle features.  
We experiment with both **linear** and **non-linear models** and compare their performance using metrics like **MSE, MAE, and R²**.

---

## 📌 Project Overview
- Analyze CO₂ emissions dataset
- Apply and compare different regression models
- Visualize predicted vs. actual emissions
- Evaluate models using error metrics

---

## ⚙️ Models Implemented
1. **Linear Regression** – Simple baseline model  
2. **Polynomial Regression** – Captures non-linear patterns  
3. **Ridge Regression** – Regularized linear model to prevent overfitting  
4. **Lasso Regression** – Regularized model with feature selection  
5. **Decision Tree Regression** – Tree-based model, handles non-linear data  
6. **Random Forest Regression** – Ensemble of decision trees for better accuracy  

---

## 📊 Evaluation Metrics
- **MSE (Mean Squared Error)**
- **MAE (Mean Absolute Error)**
- **R² Score (Coefficient of Determination)**

---

## 📈 Results Comparison

| Model                   | MSE       | MAE     | R²       |
|--------------------------|-----------|---------|----------|
| Linear Regression        | 38.04     | 3.62    | 0.9895   |
| Ridge Regression         | 32.75     | 3.16    | 0.9909   |
| Lasso Regression         | 41.42     | 3.75    | 0.9885   |
| Decision Tree Regression | 26.69     | 2.44    | 0.9926   |

> 🔑 **Best Model (so far):** Decision Tree Regression achieved the lowest errors and the highest R² score.

---

## 🔍 Visualizations
- Predicted vs. Actual CO₂ emissions plots for each model  
- Decision tree structure visualization  
- Sigmoid function (for logistic regression learning)  

---

## 🚀 How to Run
1. Open the notebook in Google Colab:  
   👉 [See Preview](https://colab.research.google.com/drive/1MpXxAMtXzBq280qNaYdI_zvmm0sOuFxS#scrollTo=8039fc5a)
2. Upload the dataset (`co2.csv`)
3. Run all cells to train and evaluate models

---

## 📂 Dataset
The dataset includes vehicle features like:
- Engine size
- Cylinders
- Fuel consumption
- CO₂ emissions

---

## 🛠️ Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

---

## 🎯 Learning Outcomes
- Understand and compare regression models
- Learn the effect of regularization (Ridge, Lasso)
- Explore tree-based methods (Decision Tree, Random Forest)
- Evaluate models using error metrics

---

✍️ *Author: [Sarthak Tripathy]*  
📌 *Machine Learning | Regression Models | CO₂ Prediction*
