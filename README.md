# 🔥 Calories Burnt Prediction - Linear Regression Model

## 📌 Overview
This repository contains a **Linear Regression model** trained to predict **calories burnt** based on various physiological and activity-related factors.
The model is built using **Python, Pandas, NumPy, Scikit-Learn**, and **Matplotlib** for visualization.

## 📂 Dataset
The dataset is sourced from **[Kaggle](https://www.kaggle.com/datasets/ruchikakumbhar/calories-burnt-prediction)** and contains the following features:
- **Gender** (0 = Female, 1 = Male)
- **Age** (years)
- **Height** (cm)
- **Weight** (kg)
- **Duration** (minutes)
- **Heart Rate** (bpm)
- **Body Temperature** (°C)
- **Calories** (target variable)

## 📊 Model Training

We trained a **Linear Regression** model with an 80-10-10 split for **training, cross-validation, and testing**.

### **🔹 Training Results**

| Dataset                    | MAE ↓    | MSE ↓    | RMSE ↓   | R² Score ↑ |
|----------------------------|----------|----------|----------|------------|
| **Training Set**            | 8.3057   | 126.4450 | 11.2448  | 0.9675     |
| **Cross-Validation Set**    | 8.3889   | 129.7156 | 11.3893  | 0.9669     |
| **Test Set**                | 8.6027   | 138.2951 | 11.7599  | 0.9652     |

### **🔹 Observations**

- The **high R² score (~96.5%)** indicates a strong predictive capability.
- **Minimal overfitting**, as training and test errors are close.
- Feature scaling and regularization could further improve generalization.

## 📈 Visualizations

The notebook includes:

- **Data distributions**
- **Pair plots** to explore feature relationships
- **Residual plots** to analyze errors

