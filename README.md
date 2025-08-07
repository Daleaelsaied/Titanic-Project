# 🛳 Titanic Survival Prediction Project

This project uses machine learning models to predict whether a passenger survived the Titanic disaster or not, based on features such as age, gender, passenger class, etc.

## 📊 Dataset
- The dataset used is the famous **Titanic dataset** from Kaggle.
- File: `train.csv`

## ⚙️ Steps

### 1. Data Cleaning
- Handled missing values in Age and Embarked.
- Dropped unnecessary columns like `Cabin`, `Ticket`.

### 2. Feature Engineering
- Extracted `Title` from Name.
- Created `FamilySize` from `SibSp + Parch`.

### 3. Data Visualization
- Plotted distributions of survival by sex, class, etc.
- Correlation heatmap to see feature relationships.

### 4. Modeling
- Used multiple models:
  - Decision Tree
  - Random Forest
  - XGBoost (best performance)
- Evaluated with Accuracy, Precision, Recall, and AUC.

### 5. Hyperparameter Tuning
- Used GridSearchCV to tune Random Forest and XGBoost parameters.

## ✅ Best Model
- **XGBoost** gave the best validation accuracy after tuning.

## 📁 Files
- `Titanic_Project.ipynb`: Full notebook with code and analysis.

## 👩‍💻 Author
- [Your Name or GitHub username here]
