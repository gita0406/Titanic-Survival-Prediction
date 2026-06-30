# Titanic Survival Prediction Model 🚢

This project is a part of my Data Science Internship Task at **SAM AI Technologies**. The objective is to build a machine learning model that predicts whether a passenger on the Titanic survived or not based on features like age, gender, ticket class, fare, etc.

## 📊 Project Overview
- **Dataset:** Titanic Passenger Dataset (containing details of individuals like Age, Sex, Pclass, Fare, SibSp, Parch).
- **Environment:** Google Colab
- **Language:** Python
- **Algorithm Used:** Random Forest Classifier

## 🛠️ Key Steps Followed
1. **Data Loading:** Imported the dataset into Pandas DataFrame.
2. **Data Cleaning:** Handled missing values in the 'Age' and 'Embarked' columns using statistical imputation. Drop unnecessary columns like Name, Ticket, and Cabin.
3. **Exploratory Data Analysis (EDA):** Visualized survival patterns based on gender and passenger class using Seaborn and Matplotlib.
4. **Feature Encoding:** Converted categorical data ('Sex', 'Embarked') into numerical values using One-Hot Encoding.
5. **Model Training:** Split the dataset into 80% Training and 20% Testing sets and trained a Random Forest Classifier.

## 🚀 Results & Performance
The model successfully evaluated passenger survival with highly optimized metrics:
- **Final Model Accuracy:** **82.12%**
- **Precision (Survived):** 0.80
- **Recall (Survived):** 0.76

### Confusion Matrix
- **True Negatives (Accurate Deceased Predictions):** 91
- **True Positives (Accurate Survival Predictions):** 41

## 📂 Repository Contents
- `Titanic_Survival_Prediction.ipynb`: The complete Google Colab python script.
- `Titanic-Dataset.csv`: Cleaned dataset utilized for model processing.
-
