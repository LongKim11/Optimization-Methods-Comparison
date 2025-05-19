# 🧱 Concrete Strength Prediction with Optimizer Analysis

This Python project analyzes and predicts **concrete compressive strength** using different optimization algorithms in machine learning. Using the [Concrete Compressive Strength Dataset](https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength) from UCI to explore how various optimizers perform in training regression models.

---

## 📊 Exploratory Data Analysis (EDA)

Before modeling, we performed comprehensive EDA to understand the dataset:

- Correlation heatmap of features
- Distribution plots of variables
- Outlier detection

---

## ⚙️ Algorithms & Optimizers

We implemented a custom regression training loop using several popular optimizers:

- Batch Gradient Descent  
- Stochastic Gradient Descent (SGD)  
- Mini-Batch Gradient Descent  
- Momentum 
- Adagrad 
- RMSProp 
- Adam

---

## 🖼️ Visualizations

- Loss curves comparing different optimizers  
- Regression performance metrics (MSE, R²)  
- Plots of predicted vs actual strength values  

---

## 📁 Dataset

- 📌 [Concrete Compressive Strength - UCI](https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength)  
- 1,030 instances, 9 numeric input variables, and 1 numeric target (compressive strength in MPa)

