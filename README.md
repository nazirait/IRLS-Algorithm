# IRLS Algorithm [Advanced Machine Learning]

Implementation of Logistic Regression from scratch using the Iterative Reweighted Least Squares (IRLS) optimization algorithm.

This project evaluates the custom implementation on both synthetic and real-world datasets and compares its performance against standard machine learning classifiers.

### Experiments:
1. Synthetic Data: Linearly separable dataset & Non-linear dataset. Testing a model with and without interaction terms

2. Real-World Datasets
  2.1 South African Heart Disease (SAheart)
   
  2.2 Water Potability Dataset

| Dataset          | Custom IRLS (Accuracy) | sklearn Logistic Regression (Accuracy) |
| ---------------- | ---------------------- | -------------------------------------- |
| SAheart          | 46.2%                  | 78.5%                                  |
| Water Potability | 53.3%                  | 59.6%                                  |


Technologies Used: Python, NumPy, pandas, scikit-learn, matplotlib

