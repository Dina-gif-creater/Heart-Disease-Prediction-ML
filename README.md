# Heart Disease Prediction using Machine Learning

## Problem Statement
The goal of this project is to predict whether a person has heart disease or not using medical attributes.
This is a binary classification problem where the output is:
- 1 → Heart Disease present
- 0 → No Heart Disease

## Dataset
- UCI Heart Disease Dataset (accessed via Kaggle)
- The dataset contains medical features such as age, sex, blood pressure, cholesterol, and heart rate.

## Algorithms Used
The following machine learning algorithms were implemented and compared:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Machine Learning Pipeline
1. Data Loading  
2. Data Cleaning (handling missing values and duplicates)  
3. Exploratory Data Analysis (EDA)  
4. Feature Selection & Feature Engineering  
5. Train-Test Split  
6. Model Training (multiple algorithms)  
7. Model Evaluation  
8. Model Comparison  
9. Best Model Selection  

## Evaluation Metrics
Each model was evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Model Comparison Summary
All models were compared based on their performance metrics.
Among them, Decision Tree and Random Forest achieved the highest accuracy and F1-score.

## Best Model
**Random Forest Classifier**

Although Decision Tree and Random Forest showed similar performance, Random Forest was selected as the final model because:
- It reduces overfitting
- It is more stable and reliable
- It generalizes better on unseen data

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Conclusion
This project demonstrates a complete end-to-end machine learning workflow.
By comparing multiple algorithms, Random Forest was identified as the most suitable model for heart disease prediction.
The project highlights the importance of data preprocessing, model comparison, and proper evaluation in real-world ML problems.
