# 🚗 Car Price Prediction Using Machine Learning

A machine learning project that predicts used car prices using **Linear Regression** and explores how different categorical encoding techniques affect model performance.

## 📌 Project Overview

The goal of this project is to predict the selling price of a used car based on its features, such as model, year, transmission, mileage, fuel type, tax, fuel economy, and engine size.

This project explores data preprocessing, categorical encoding, feature scaling, model training, and evaluation using Python and Scikit-learn.

## 🎯 Objectives

- Understand and preprocess a real-world car dataset.
- Apply Label Encoding and One-Hot Encoding to categorical features.
- Standardize numerical features using `StandardScaler`.
- Train a Linear Regression model for price prediction.
- Compare model performance using different encoding approaches.

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Kaggle Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Algorithm:** Linear Regression
- **Preprocessing:** Label Encoding, One-Hot Encoding, StandardScaler

## 📊 Dataset

The project uses a used-car dataset containing vehicle specifications and selling prices.

Features explored include:

- `model` — car model
- `year` — manufacturing year
- `transmission` — transmission type
- `mileage` — distance driven
- `fuelType` — fuel category
- `tax` — vehicle tax
- `mpg` — miles per gallon
- `engineSize` — engine capacity
- `price` — target variable

*Dataset source: Add the original Kaggle dataset link here.*

## ⚙️ Workflow

1. **Data preparation:** Separate input features (`X`) from the target (`price`).
2. **Categorical encoding:** Compare Label Encoding and One-Hot Encoding.
3. **Feature scaling:** Apply StandardScaler to selected numerical features.
4. **Model training:** Train Linear Regression models.
5. **Evaluation:** Compare the reported model scores.

## 📈 Results

In my initial experiments, the One-Hot Encoding approach achieved a reported score of approximately **84%**, while the Label Encoding approach achieved approximately **74%**.

| Approach | Reported score |
|---|---:|
| One-Hot Encoding | 84% |
| Label Encoding | 74% |


## 🧠 Key Learnings

- How categorical features can be represented numerically.
- Differences between Label Encoding and One-Hot Encoding.
- Why feature scaling is used in machine learning.
- How to train and evaluate a regression model.
- How preprocessing choices can affect model performance.

## 🚀 Future Improvements

- Compare Linear Regression with Random Forest and Gradient Boosting regressors.
- Evaluate performance using R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
- Use cross-validation and hyperparameter tuning.
- Build a reusable preprocessing and modeling pipeline.
- Deploy the trained model as a simple web application.

## ▶️ How to Run

1. Open the notebook in Kaggle or Jupyter Notebook.
2. Download or attach the required dataset.
3. Install the required Python libraries if they are not already available.
4. Run the notebook cells in order.

## 👨‍💻 Author

**Akhil Pandey**

Aspiring AI/ML Engineer | Exploring Machine Learning, Data Science, and Python.
