# 🏠 House Price Prediction using Machine Learning

A Machine Learning project that predicts house prices based on various housing features. This project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, hyperparameter tuning, and model evaluation using multiple regression algorithms.

---

## 📌 Project Overview

House price prediction is one of the most common regression problems in Machine Learning. The objective of this project is to build predictive models capable of estimating house prices accurately by learning patterns from historical housing data.

Three regression algorithms were implemented and compared:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

The best-performing model was selected based on evaluation metrics.

---

## 🎯 Problem Statement

The goal of this project is to develop a regression model that can accurately predict house prices using available property features.

---

## 📂 Dataset

The dataset contains information related to residential houses, including several numerical and categorical attributes that influence property prices.

Typical features include:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Stories
- Parking
- Furnishing Status
- Main Road Access
- Guest Room
- Basement
- Air Conditioning
- Preferred Area
- Price (Target Variable)

---

## ⚙️ Project Workflow

```
Data Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Model Evaluation
        │
        ▼
Model Comparison
```

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed before training the models:

- Loaded the housing dataset
- Checked dataset structure
- Handled missing values (if present)
- Converted categorical variables into numerical values
- Feature scaling and normalization
- Split the dataset into training and testing sets (80:20)

---

## 🤖 Machine Learning Models

### 1. Linear Regression

A baseline regression model used for comparison.

### 2. Random Forest Regressor

Random Forest was optimized using **RandomizedSearchCV** to identify the best hyperparameters.

### 3. XGBoost Regressor

XGBoost was also tuned using **RandomizedSearchCV**, achieving the best prediction performance among all models.

---

## 📊 Model Evaluation

The models were evaluated using the following metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Performance Comparison

| Model | RMSE | R² Score |
|--------|------|----------|
| Linear Regression | **0.5325** | **0.6356** |
| Random Forest Regressor | **0.3968** | **0.7976** |
| XGBoost Regressor | **0.3804** | **0.8140** |

---

## 🏆 Best Model

**XGBoost Regressor**

Performance:

- RMSE: **0.3804**
- R² Score: **0.8140**

The XGBoost model produced the lowest prediction error and the highest coefficient of determination, making it the most accurate model for this dataset.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── House_Prediction_Price.ipynb
├── README.md
└── dataset/
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/krishshah8000/House-Price-Prediction.git
```

### Move into the project directory

```bash
cd House-Price-Prediction
```

### Install dependencies

```bash
pip install pandas numpy scikit-learn xgboost matplotlib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
House_Prediction_Price.ipynb
```

Run all cells sequentially.

---

## 📈 Results

- Successfully trained three regression models.
- Hyperparameter tuning improved the performance of ensemble models.
- XGBoost achieved the best predictive accuracy.
- Tree-based ensemble models significantly outperformed Linear Regression.

---

## 🔮 Future Improvements

- Deploy the model using Flask or Streamlit
- Perform advanced feature engineering
- Apply cross-validation
- Experiment with CatBoost and LightGBM
- Build an interactive web application for house price prediction

---

## 👨‍💻 Author

**Krish Shah**

GitHub: https://github.com/krishshah8000

---

## ⭐ If you found this project useful, consider giving it a star!
