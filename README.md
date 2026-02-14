# 📊 Students-Performance-Factor
📌 Project Overview

This project focuses on building a machine learning model to predict students' exam scores based on their study hours.
The goal is to understand the relationship between study time and academic performance using linear regression techniques.

The dataset used is Student Performance Factors from Kaggle.

🎯 Objectives

Clean and preprocess the dataset

Perform Exploratory Data Analysis (EDA)

Visualize relationships between features and exam scores

Build a Linear Regression model based on study hours

Evaluate model performance

(Bonus) Apply Polynomial Regression and compare results

📂 Dataset Description

The dataset contains various student-related factors including:

Hours Studied

Attendance

Gender

Parental Education

Exam Score (Target Variable)

Other performance-related features

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

📈 Steps Performed
1. Data Cleaning

Handled missing values using median and mode

Checked and removed duplicates

2. Exploratory Data Analysis (EDA)

Correlation heatmap

Distribution plots

Relationship between study hours and exam scores

Analysis of categorical features

3. Model Building

Split data into training and testing sets

Trained a Linear Regression model using study hours

Evaluated using:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

4. Bonus

Applied Polynomial Regression

Compared performance with Linear Regression

📊 Results

Linear Regression showed a strong positive relationship between study hours and exam scores

Polynomial Regression did not significantly outperform the linear model (expected due to near-linear relationship)

The model successfully demonstrates how study time impacts academic performance

📌 Key Insights

Increased study hours generally lead to higher exam scores

Some additional factors (attendance, parental education) may further improve prediction accuracy

Simple models can perform well for clearly linear relationships

🚀 Future Improvements

Train models using multiple features instead of a single variable

Try advanced models like Random Forest or XGBoost

Perform feature importance analysis

Hyperparameter tuning
