# 🚢 Titanic Survival Prediction - Machine Learning Project

This project uses machine learning algorithms to predict whether a passenger survived the Titanic shipwreck based on features like age, gender, ticket class, and fare.

---

## 📁 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- File used: `train.csv`

---

## 🧰 Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Google Colab

---

## 🔍 Problem Statement

Given passenger information (e.g., name, age, sex, class), can we predict whether they survived the Titanic disaster?

---

## 📊 Features Used

| Feature     | Description                        |
|-------------|------------------------------------|
| Pclass      | Ticket class (1st, 2nd, 3rd)       |
| Sex         | Gender (male, female)              |
| Age         | Age in years                       |
| SibSp       | # of siblings/spouses aboard       |
| Parch       | # of parents/children aboard       |
| Fare        | Ticket fare                        |
| Embarked    | Port of Embarkation (C, Q, S)      |

---

## 🧹 Data Preprocessing

- Filled missing values in `Age` and `Embarked`
- Dropped `Cabin`, `Name`, `Ticket`, and `PassengerId`
- Used `LabelEncoder` to convert `Sex` and `Embarked` into numerical format

---

## 🤖 Models Used

### Logistic Regression
- Simple baseline model
- Accuracy: ~78%

### Random Forest Classifier
- Higher accuracy with better generalization
- Accuracy: ~83%

---

## 📈 Results

![Accuracy Comparison](https://via.placeholder.com/400x200.png?text=Bar+Chart+of+Model+Accuracy)

> Random Forest outperformed Logistic Regression.

---

## 📌 Key Learnings

- Learned how to preprocess categorical and numerical data
- Understood the basic concepts of classification models
- Built and evaluated predictive models using `scikit-learn`

---

## 🗂️ Project Structure


---

## 🚀 Future Improvements

- Add more feature engineering (e.g., title from name)
- Try hyperparameter tuning using `GridSearchCV`
- Test more models like KNN, SVM
- Deploy with Streamlit or Flask

