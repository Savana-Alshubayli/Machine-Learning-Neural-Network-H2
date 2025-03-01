# Machine Learning Homework 2: Neural Network for Diamond Price Prediction

## 📌 Overview
This repository contains my **Machine Learning Homework 2**, where I build and train a **feedforward neural network** to predict diamond prices using the **Diamonds dataset**.

The model is implemented using **TensorFlow/Keras** and follows these steps:
- Data Preprocessing (One-hot encoding, Standardization)
- Building a Two-Layer Feedforward Neural Network
- Training with **Adam Optimizer** (Learning Rates: `0.001` and `0.3`)
- Evaluating Performance (MSE, MAE, R² Score)
- Visualizing Predictions vs. Actual Prices

---

## 📊 Dataset
- The dataset used is **Diamonds** from Seaborn (`sns.load_dataset("diamonds")`).
- Features include **carat, cut, color, clarity, depth, table, x, y, z**.
- The target variable is **price** (regression task).

---

## 🚀 Model Architecture
- **Input Layer:** Features from the dataset
- **Hidden Layer 1:** 10 neurons, ReLU activation
- **Hidden Layer 2:** 5 neurons, ReLU activation
- **Output Layer:** 1 neuron (Regression)

---

## 📉 Training & Evaluation
The model is trained using **two learning rates** to compare performance:
1. **Learning Rate = 0.001** (Stable Learning)
2. **Learning Rate = 0.3** (Faster, but Unstable)

Performance Metrics:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R² Score** (How well the model fits the data)

---

## 📈 Results
- The **lower learning rate (0.001)** resulted in a **smooth** training process and **better accuracy**.
- The **higher learning rate (0.3)** caused **fluctuations**, leading to unstable convergence.

The loss curves and scatter plots of **predicted vs. actual prices** are available in the Jupyter Notebook.

---

## 🔧 How to Run the Notebook

### **📌 Option 1: Run on Google Colab (Recommended)**
1. **Go to Google Colab** → [Google Colab Homepage](https://colab.research.google.com/)
2. Click **File → Open Notebook**.
3. Go to the **GitHub tab** and enter the repository URL
