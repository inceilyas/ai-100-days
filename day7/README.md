# Google Ads Sales Prediction

This project builds a neural network model using TensorFlow/Keras to predict sales amount based on Google Ads campaign data.

## 📊 Dataset

- **Source**: [Google Ads Sales Dataset on Kaggle](https://www.kaggle.com/datasets/nayakganesh007/google-ads-sales-dataset/data)
- Contains features such as campaign name, ad type, impressions, device type, clicks, etc.
- Target variable: `Sales_Amount`

## 🧠 Model Architecture

A regression model with the following architecture:
- Dense(128) + BatchNormalization + Dropout(0.3)
- Dense(64) + BatchNormalization + Dropout(0.3)
- Dense(32) + BatchNormalization
- Output: Dense(1)

**Loss**: Mean Squared Error  
**Optimizer**: Adam  
**Metrics**: MAE (Mean Absolute Error)

## 🛠️ Features

- Data preprocessing (date parsing, one-hot encoding, scaling)
- Batch Normalization for faster convergence
- Dropout for regularization
- EarlyStopping based on validation loss

## 📈 Results

- Model converges well with minimal overfitting
- Predicts sales amount with reasonable accuracy
- Evaluation via MAE and MSE

## 🔍 Visualization

- Training vs validation loss and MAE curves
- Actual vs predicted sales plot

---

Let me know if you'd like a version that includes code snippets or metrics summary.

