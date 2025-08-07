# 🚢 Titanic Survival Prediction

This project uses the Titanic dataset to predict passenger survival using machine learning models.

## 📄 Dataset Features

- `Pclass`, `Sex`, `Age`, `Fare`, `SibSp`, `Parch`, `Embarked`, etc.
- Target: `Survived` (0 = No, 1 = Yes)

## 🧼 Preprocessing

- Handled missing values (Age, Embarked)
- Converted categorical to numerical (Sex, Embarked)
- Dropped irrelevant features (Cabin, Ticket, Name, PassengerId)

## 🤖 Models Used

- Logistic Regression
- Random Forest
- SVM
- KNN

**Best model:** `Random Forest Classifier`  
**Accuracy:** 0.81 (81%)

## ▶️ How to Run

1. Install dependencies:  
   `pip install -r requirements.txt`
2. Run the notebook:  
   `jupyter notebook Task1_TitanicSurvival.ipynb`

