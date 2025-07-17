# 🛳️ Titanic - Machine Learning from Disaster

This repository contains my solution to the classic **Kaggle Titanic: Machine Learning from Disaster** competition. The task is to build a machine learning model that predicts which passengers survived the Titanic shipwreck.

## 📌 Competition Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. The goal is to use passenger data (such as age, sex, class, etc.) to predict whether they survived or not.

- **Target Variable**: `Survived` (0 = No, 1 = Yes)
- **Input Features**: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.

You can find the competition [here](https://www.kaggle.com/competitions/titanic/overview).

---

## 📁 Project Structure

```
├── data/
│   ├── train.csv
│   ├── test.csv
├── submission.csv
├── titanic_model.ipynb
├── README.md
```

---

## 🧠 Approach

### 1. **Data Cleaning**
- Handled missing values in `Age`, `Cabin`, and `Embarked`
- Converted categorical variables using Label Encoding / One-Hot Encoding

### 2. **Feature Engineering**
- Created new features such as:
  - `FamilySize = SibSp + Parch + 1`
  - `IsAlone` flag
  - Extracted `Title` from `Name`

### 3. **Modeling**
- Used **[Your model here]**, e.g., `RandomForestClassifier`, `LogisticRegression`, `XGBoost`, etc.
- Performed hyperparameter tuning using cross-validation

### 4. **Evaluation**
- Evaluated using accuracy on validation split
- Final predictions made on test set and saved in `submission.csv`

---

## 📊 Performance

| Metric   | Score    |
|----------|----------|
| Accuracy | 0.7655   |


---

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Basic packages used:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `xgboost`

---

## 🚀 Usage

1. Clone the repository
2. Run the notebook:
   ```
   jupyter notebook titanic_model.ipynb
   ```
3. Generate submission:
   - The notebook will produce `submission.csv` formatted for Kaggle.

---

## ✅ To Do

- [ ] Try ensemble models
- [ ] Improve feature selection
- [ ] Use grid search or Optuna for better tuning

---

## 📬 Contact

Feel free to reach out via mehmetilyasince1@gmail.com

---

