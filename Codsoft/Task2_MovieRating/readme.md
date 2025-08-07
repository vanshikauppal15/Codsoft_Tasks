# 🎬 Movie Rating Prediction

This project builds a machine learning model to predict the rating of a movie based on features like genre, director, and actors.

## 🎯 Objective

Analyze historical movie data and develop a regression model that estimates ratings given by users or critics.

## 📄 Features Used

- `Genre`
- `Director`
- `Actors`
- `Budget`
- `Runtime`
- `Release Year`

## 🧼 Preprocessing

- Handled missing values
- Converted categorical features (e.g., Genre, Director, Actors) to numerical using encoding techniques
- Performed feature selection and scaling

## 🤖 Model Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

**Best model:** `Random Forest Regressor`  
**R² Score:** 0.83  
**RMSE:** 0.52

## ▶️ How to Run

1. Install dependencies:  
   `pip install -r requirements.txt`
2. Run the notebook:  
   `jupyter notebook Task2_MovieRating.ipynb`
