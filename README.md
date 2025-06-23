# Heart Failure Detection using Ensemble Learning

This project applies ensemble machine learning techniques to predict heart failure events based on clinical records. It utilizes models like Random Forest, XGBoost, MLP, and a Stacking Classifier.

## 📊 Dataset

- Source: [Heart Failure Clinical Records Dataset](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)
- Size: 299 records
- Target: `DEATH_EVENT` (1 - Event occurred, 0 - No event)

## ⚙️ Models Used

- Random Forest Classifier
- XGBoost Classifier
- MLP Classifier (Neural Network)
- Stacking Classifier (Ensemble)

## 📈 Features

- Feature Importance Visualization (Random Forest)
- Training and Validation Loss Curves (XGB, MLP)
- Confusion Matrix
- Accuracy & F1 Score Evaluation
- Predictions Comparison Heatmap
- Model Accuracy Comparison Bar Chart

## 🧪 Libraries Required

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn

## Cite
N. N. Reddy, N. Lingadally, M. Shereesha and T. Shilpa, "A Comprehensive Ensemble Approach with Real-Time Performance Metrics for Heart Failure Prediction," 2024 First International Conference for Women in Computing (InCoWoCo), Pune, India, 2024, pp. 1-6, doi: 10.1109/InCoWoCo64194.2024.10863522.
