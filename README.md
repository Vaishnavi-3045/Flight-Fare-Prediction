# ✈️ Flight Fare Prediction

## 📌 Project Overview
Flight ticket prices vary based on several factors, including airline, route, duration, number of stops, and journey timing. This project uses machine learning techniques to analyze flight data and predict ticket prices.

## 🎯 Objectives
- Analyze flight pricing patterns.
- Perform data cleaning and preprocessing.
- Explore important factors affecting ticket prices.
- Build and compare machine learning regression models.
- Tune the best-performing model.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## 🔄 Project Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Feature engineering
4. Exploratory Data Analysis (EDA)
5. Outlier handling
6. Categorical feature encoding
7. Train-test split
8. Model training and comparison
9. Hyperparameter tuning
10. Model evaluation

## 🤖 Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## 📊 Model Performance

| Model | R² Score |
|---|---:|
| Linear Regression | 0.6146 |
| Random Forest | 0.7816 |
| XGBoost | 0.8269 |

XGBoost performed best among the initial models.

## 🔧 Hyperparameter Tuning
RandomizedSearchCV with 5-fold cross-validation was used to tune the XGBoost model.

The reported mean cross-validation R² score was **0.8817**.

## 💡 Key Learnings
- Data preprocessing and feature engineering are essential for model performance.
- Flight prices are influenced by multiple variables.
- Ensemble models can perform effectively on structured data.
- Hyperparameter tuning can improve model performance.

## 🏁 Conclusion
This project demonstrates an end-to-end machine learning workflow for flight fare prediction, from data exploration and preprocessing to model training, comparison, and tuning.

---
**Author:** Thodkar Vaishnavi
