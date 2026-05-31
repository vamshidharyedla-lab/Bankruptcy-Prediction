# **BANKRUPTCY PREDICTION**

In this notebook, we work with financial data to predict company bankruptcy. The dataset includes 95 features and 6,819 companies.

We start with exploratory data analysis (EDA), including visualizations like correlation heatmaps, to understand the data better. Then, we build some basic models using Logistic Regression, XGBoost, and Random Forest.

To improve model performance, we tune the hyperparameters using grid search or random search. After tuning, we compare the models and evaluate their performance with the business goal in mind.

A common mistake in this kind of problem is using SMOTE (Synthetic Minority Oversampling Technique) on the test set, which leads to unrealistically high F1 scores. Since the dataset has a class imbalance, the real challenge is building a model that handles this imbalance well during testing.
