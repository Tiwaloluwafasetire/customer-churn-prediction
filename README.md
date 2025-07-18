# customer-churn-prediction
Machine learning project to predict telecom customer churn
# Telecom Customer Churn Prediction

![Feature Importance](images/feature_importance.png)

## Project Overview
Predicts which customers will cancel service using machine learning. Identifies key risk factors for targeted retention.

## Key Results
| Model               | Accuracy | Recall | Precision |
|---------------------|----------|--------|-----------|
| Logistic Regression | 73%      | 80%    | 49%       |
| Random Forest       | 79%      | 49%    | 63%       |

**Best Model**: Random Forest (higher accuracy & precision)

## How to Run
1. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Open notebook:
   ```bash
   jupyter notebook notebooks/churn_analysis.ipynb
   ```

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/customer-churn-prediction/blob/main/notebooks/churn_analysis.ipynb)
