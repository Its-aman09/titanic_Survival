# Titanic Survival Prediction

An end-to-end Machine Learning project to predict the survival of Titanic passengers using Python. This project includes data preprocessing, feature engineering, model training, evaluation, and an interactive web application for real-time predictions.

---

## Project Overview
This project predicts the likelihood of survival for passengers aboard the Titanic based on features like age, gender, passenger class, fare, and family members. The project demonstrates a complete ML pipeline and interactive deployment:

- **Model Used:** Random Forest Classifier  
- **Features:** Age, Gender, Passenger Class (Pclass), Fare, Number of Siblings/Spouses (SibSp), Number of Parents/Children (Parch)  
- **Deployment:** Streamlit app with real-time predictions  
- **Dataset:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

---

## Features
- Cleaned and preprocessed the dataset (handled missing values, removed duplicates, encoded categorical variables).  
- Trained multiple models including Logistic Regression, Decision Tree, SVM, and Random Forest.  
- Random Forest selected for best performance based on accuracy and feature importance.  
- Interactive Streamlit UI for entering passenger details and predicting survival probability.  
- Publicly deployable using ngrok for live testing.

---

## Installation

1. Clone this repository:
```bash
git clone https://github.com/<your-username>/titanic-survival-prediction.git
