
# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview

This project predicts house prices using **Machine Learning Regression models**. The model is trained on the **House Price India** dataset using key housing features such as:

* Living Area
* Number of Bedrooms
* Number of Bathrooms

The project compares the performance of three regression algorithms:

* Linear Regression
* Ridge Regression
* Lasso Regression

After training, the best-performing model is used to predict the price of a new house based on user input.

---

## 🎯 Objective

The objective of this project is to build a regression model that accurately predicts house prices based on important property characteristics and compares different linear regression techniques.

---

## 📂 Dataset

**Dataset:** `House Price India.csv`

### Features Used

| Feature             | Description                    |
| ------------------- | ------------------------------ |
| living area         | Total living area of the house |
| number of bedrooms  | Number of bedrooms             |
| number of bathrooms | Number of bathrooms            |

### Target Variable

* **Price** – Selling price of the house.

---

## 🛠 Technologies Used

* Python
* Pandas
* Scikit-learn

---

## 📚 Libraries

```python
pandas
scikit-learn
```

Modules used:

* train_test_split
* StandardScaler
* LinearRegression
* Ridge
* Lasso
* r2_score
* mean_absolute_error

---

## ⚙️ Project Workflow

### 1. Load Dataset

The dataset is loaded using Pandas.

### 2. Feature Selection

The following features are selected:

* Living Area
* Number of Bedrooms
* Number of Bathrooms

The target variable is:

* Price

### 3. Data Splitting

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

### 4. Data Preprocessing

Feature scaling is performed using **StandardScaler** to normalize the input variables before training.

### 5. Model Training

Three regression algorithms are trained:

* Linear Regression
* Ridge Regression
* Lasso Regression

### 6. Model Evaluation

The models are evaluated using the **R² Score**, which measures how well the predicted values match the actual house prices.

### 7. House Price Prediction

The trained Ridge Regression model accepts user inputs:

* Living Area
* Number of Bedrooms
* Number of Bathrooms

It then predicts the estimated house price.

---

## 📈 Evaluation Metric

The project uses:

* **R² Score (Coefficient of Determination)**

Higher R² values indicate better predictive performance.

---

## 💻 Example Input

```
Enter area: 1800
Enter bedrooms: 3
Enter bathrooms: 2
```

### Example Output

```
Predicted House Price: ₹8,750,000
```

*(Example value only.)*

---

## 📊 Machine Learning Models Compared

| Model             | Purpose                                            |
| ----------------- | -------------------------------------------------- |
| Linear Regression | Baseline regression model                          |
| Ridge Regression  | Reduces overfitting using L2 regularization        |
| Lasso Regression  | Performs feature selection using L1 regularization |

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── House Price India.csv
├── house_price_prediction.py
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

* Include additional features such as location, age of the house, and parking availability.
* Perform hyperparameter tuning for Ridge and Lasso regression.
* Add visualization of feature relationships and model performance.
* Build a web application using Flask or Streamlit for interactive predictions.
* Explore advanced regression models such as Random Forest, XGBoost, and Gradient Boosting for improved accuracy.

---

## 🎓 Learning Outcomes

Through this project, you will learn:

* Data preprocessing using Pandas
* Feature scaling with StandardScaler
* Train-test data splitting
* Regression model implementation
* Regularization techniques (Ridge and Lasso)
* Model evaluation using R² Score
* Predicting real-world values using trained machine learning models

---

## ✅ Conclusion

This project demonstrates a complete machine learning workflow for predicting house prices. By comparing Linear Regression, Ridge Regression, and Lasso Regression, it highlights the impact of regularization techniques on model performance. The final model can estimate house prices from user-provided property details, making it a practical example of supervised learning for regression tasks.
