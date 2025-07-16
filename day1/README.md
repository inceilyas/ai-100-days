# 🧠 Model Comparison: With and Without Train-Test Split

This project compares the performance of several machine learning models under two conditions:
- ✅ Without train-test split (trained & tested on full dataset)
- ✅ With train-test split (70% train, 30% test)

---

## 📊 Models Evaluated

The following models are implemented and compared:

| Model                | Description                      |
|---------------------|----------------------------------|
| Linear Regression    | Baseline regression model        |
| Logistic Regression  | Classification using sigmoid     |
| Decision Tree        | Tree-based non-linear classifier |
| Random Forest        | Ensemble of decision trees       |
| XGBoost              | Gradient-boosted tree ensemble   |

---

## ⚙️ Dataset

- **Heart Attack Prediction Dataset** from [Kaggle] (shared in repository)
- 303 samples, 13 features
- Target variable: `output` (binary classification)

---

## 📐 Evaluation Metric

- `.score()` method of each model
  - For classification: Accuracy
  - For regression: R² score

---

## 🪄 Visualizations

- **Two tables** comparing model scores:
  - One using full dataset (no split)
  - One using train/test split
- **Bar chart** for side-by-side comparison of model performances

---

## 📦 Libraries Used

- `scikit-learn`
- `xgboost`
- `matplotlib`
- `pandas`, `numpy`

---

## 📌 How to Run

1. Install requirements:

```bash
pip install scikit-learn xgboost matplotlib pandas
