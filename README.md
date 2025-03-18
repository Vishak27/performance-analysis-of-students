# Performance Analysis of Student

## Overview
This project analyzes student performance using machine learning algorithms in R. The goal is to predict student academic outcomes based on various factors like demographics, study habits, and previous grades. The dataset consists of student records from Portuguese schools.

## Project Objective
- Perform student performance analysis using supervised and unsupervised machine learning algorithms.
- Provide visualizations to interpret student performance trends.
- Evaluate algorithm accuracy for prediction.

## Dataset
- **Source**: Kaggle (Student Performance Dataset)
- Contains student grades, demographic information, and study-related attributes.
- **Target Variable**: G3 (Final Year Grade)

## Methodology
The following algorithms were applied using **R**:
1. **K-Means Clustering**: To group students based on similarities.
2. **Decision Tree**: For classification and understanding influencing factors.
3. **Support Vector Machine (SVM)**: For predictive analysis.
4. **Linear Regression**: For predicting continuous values (Final Grades).

## Results
- The decision tree algorithm provided insights into factors influencing student performance.
- SVM showed reasonable classification accuracy.
- Linear regression demonstrated a strong correlation between G1, G2, and G3 grades.
- K-Means identified patterns in student performance groups.

## Tools and Libraries
- **R** and **RStudio**
- Libraries: `caret`, `ggplot2`, `e1071`, `rpart`

## Conclusion
The analysis provides actionable insights into student performance, aiding educators in identifying areas for improvement. Future work could include additional feature engineering and testing other machine learning models for better accuracy.
