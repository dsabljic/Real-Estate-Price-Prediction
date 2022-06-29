# Real-Estate-Price-Prediction

Dataset: https://www.kaggle.com/datasets/quantbruce/real-estate-price-prediction?ref=hackernoon.com&select=Real+estate.csv

The linear regression algorithm is firstly implemented *by hand* meaning I wrote the functions for computing cost, gradient for given parameters *w* and *b* along with my own implementation of gradient descent and z-score normalization. With that being said, this is by no means a well optimized or even vectorized implementation of linear regression (very few things are vectorized to the fullest, for clarity sake). Later on, the notebook provides production-like solution to the given problem using scikit-learn's SGDRegressor for finding optimal parameters and StandardScaler for the before mentioned z-score normalization.
