# Titanic Survival Prediction - Machine Learning Classifier

## Project Objective
The goal of this project is to predict the survival of passengers aboard the Titanic using machine learning algorithms. This is a **binary classification problem** where the target variable is:
- `1` → Survived
- `0` → Did not survive

---

## Dataset Description
**Dataset Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

**Features Used:**
- Pclass (Passenger Class)
- Sex
- Age
- SibSp (Number of Siblings/Spouses Aboard)
- Parch (Number of Parents/Children Aboard)
- Fare
- Embarked (Port of Embarkation)

**Target:**
- Survived (0 or 1)

---

## Data Processing Steps
- **Dropped unnecessary columns**: `Name`, `Ticket`, `Cabin`, `PassengerId`
- **Handled Missing Values**:
  - `Age` → Replaced missing values with the median
  - `Embarked` → Replaced missing values with the mode
  - `Fare` → Replaced missing values with the median (if any)
- **Encoded Categorical Columns**: `Sex` and `Embarked` using Label Encoding
- **Train-Test Split**: 80% training, 20% testing

---

## Model Selection & Performance Analysis
The following machine learning models are trained, tested, and evaluated:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Naive Bayes
- K-Nearest Neighbors (KNN)

The best model is selected based on the highest accuracy.

---

## Requirements
Create a `requirements.txt` with:

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## How to Run
### Clone the Repository
```bash
git clone https://github.com/Ratheesh1104/ML-Titanic-Survival-Prediction.git
cd titanic-survival-prediction
```

