# India Crime Rate Classification

This project analyzes and classifies Indian states and union territories based on crime rates using the [India Crime Data (2001-2013)](https://www.kaggle.com/datasets/divyanshnegi2735/india-crime-data-wrt-population-statewise2001-13/data) dataset.  
We engineered a "high crime rate" label by thresholding per-100k crime statistics, then compared the performance of various machine learning classifiers to predict whether a region has a high crime rate.

## Steps
- Data preprocessing and feature engineering
- Encoding categorical features (state/ut)
- Training multiple classifiers (Logistic Regression, Ridge, Decision Tree, Random Forest, etc.)
- Comparing model performance with accuracy scores and visualizing results

## Requirements
- Python 3.x
- pandas, scikit-learn, matplotlib

## How to run
1. Install dependencies:  
   `pip install -r requirements.txt`
2. Run the notebook:  
   `indiaCrime.ipynb`

---

**Dataset:**  
[India Crime Data (Kaggle)](https://www.kaggle.com/datasets/divyanshnegi2735/india-crime-data-wrt-population-statewise2001-13/data)
