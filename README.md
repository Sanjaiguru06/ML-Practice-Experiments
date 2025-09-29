EXPERIMENT LINKS:

Experiment 1 - https://colab.research.google.com/drive/1atiEeJ-CtyeYz5VEu3zGuI0O7m56sm8l?usp=sharing

Experiment 2 - https://colab.research.google.com/drive/1P6hyedHQTM-wZquJVppqYcYURKDc4F2c?usp=sharing

Experiment 3 - https://colab.research.google.com/drive/1XUflZQ0oLGf8NX7dhGmrt3ZRky0D_QOt?usp=sharing

Experiment 4 - https://colab.research.google.com/drive/1JSN6Eg3fBusOuEFOiSc1HQ0mdrpo61BZ?usp=sharing

Polynomial Regression Curve - https://colab.research.google.com/drive/103bFytOq5tO-svF-7umuSR6L0P1pGJSa?usp=sharing

ML Experiments on Heart Disease Dataset

This repository contains 4 Machine Learning experiments using a heart disease-related dataset (dataset.csv). The experiments explore both regression and classification techniques to predict numeric and categorical outcomes.

Dataset

File: dataset.csv

Contains patient data such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, etc.

Used for both regression (predicting cholesterol) and classification (predicting sex or chest pain type).

Experiments
Experiment 1: Data Exploration and Preprocessing

Performed basic EDA (exploratory data analysis).

Checked for missing values, categorical features, and numeric distributions.

Prepared data for modeling using encoding for categorical features.

Experiment 2: Regression Analysis (Heart Disease Prediction)

Implemented Linear Regression to predict cholesterol.

Split dataset into training and testing sets.

Evaluated using Mean Squared Error (MSE) and R² score.

Visualized Actual vs Predicted values.

Experiment 3: Polynomial Regression (Curve Fitting)

Applied Polynomial Regression on synthetic data to test degree 1, 3, 5, 6.

Observed underfitting (degree 1), good fit (degree 3, 5), and slight overfitting (degree 6).

Visualized polynomial fits to understand model complexity.

Experiment 4: Classification

Implemented Bayesian Logistic Regression and Support Vector Machine (SVM) for classification tasks.

Predicted sex (0/1) or chest pain type as the target.

Standardized features for SVM.

Evaluated using accuracy, classification report, and confusion matrix.

Technologies Used

Python 3

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
 
