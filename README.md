# Codsoft_Tasks


This repository contains three beginner-friendly machine learning projects built using Python. Each project focuses on applying different ML techniques to solve real-world problems like survival prediction, movie rating estimation, and sales forecasting.

---

## 🚢 1. Titanic Survival Prediction

Predict whether a passenger survived the Titanic disaster based on features like age, gender, and ticket class.

### Features Used
- `Pclass`, `Sex`, `Age`, `Fare`, `SibSp`, `Parch`, `Embarked`, etc.

### Preprocessing
- Handled missing values
- Encoded categorical variables
- Dropped irrelevant features

### Models Used
- Logistic Regression
- Random Forest
- SVM
- KNN

**Best Model:** Random Forest Classifier  
**Accuracy:** 0.81

---

## 🎬 2. Movie Rating Prediction

Predict the rating of a movie using metadata such as genre, director, and actors.

### Features Used
- `Genre`, `Director`, `Actors`, `Budget`, `Runtime`, `Release Year`

### Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature scaling and selection

### Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

**Best Model:** Random Forest Regressor  
**R² Score:** 0.83  
**RMSE:** 0.52

---

## 📈 3. Sales Prediction

Predict future sales using advertising data and customer insights.

### Features Used
- `TV`, `Radio`, `Newspaper` advertising spend
- `Product Type`, `Target Audience`

### Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature selection and scaling

### Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

**Best Model:** Random Forest Regressor  
**R² Score:** 0.89  
**RMSE:** 1.27

---

## ▶️ How to Run Any Project

1. Install dependencies:  
   `pip install -r requirements.txt`

2. Run the desired notebook using:  
   `jupyter notebook <Notebook_Name>.ipynb`

Projects included:
- `Task1_TitanicSurvival.ipynb`
- `Task2_MovieRating.ipynb`
- `Task3_SalesPrediction.ipynb`
