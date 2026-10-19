# README – Student Performance Prediction Using Boosting

**Project Title:** Student Performance Prediction Using Gradient Boosting Regression  
**Domain:** Artificial Intelligence and Machine Learning (AIML)

## 1. Project Overview
This project aims to analyze student performance factors and predict students' exam scores using a machine learning technique called Gradient Boosting Regression. The project explores how factors such as study hours, attendance, previous scores, parental involvement, and other student-related characteristics are associated with exam performance.

## 2. Dataset Description
The project uses the `StudentPerformanceFactors.csv` dataset. It contains **6,607 rows and 20 columns**, including student-related factors and the target column, `Exam_Score`. The dataset is used to explore patterns in student performance and develop a model for predicting exam scores.

## 3. Project Objectives
- Understand and explore the student performance dataset.
- Identify and handle missing values and check for duplicate records.
- Visualize relationships between student-related factors and exam scores.
- Build a Gradient Boosting Regression model to predict exam scores.
- Evaluate the model and interpret its results.

## 4. Tools and Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## 5. Methodology
The dataset is loaded and inspected using Pandas. Missing values are identified, and the missing categorical entries are handled using the most frequent category. Duplicate records and data types are checked. Exploratory Data Analysis (EDA) is performed using graphs and statistical summaries. Categorical features are converted into numerical representations using one-hot encoding. The dataset is divided into training and testing sets, and a Gradient Boosting Regression model is trained to predict `Exam_Score`.

## 6. Model Evaluation
The model is evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R-squared (R²) score. These metrics help measure prediction errors and assess how well the model explains variations in exam scores. Actual and predicted scores are also compared to understand model performance.

## 7. Expected Outcome
The project aims to identify patterns in student performance and develop a model that estimates exam scores from the available features. The final findings and model performance will be reported based on the actual results obtained during execution.

## 8. Conclusion
This project provides practical experience in data cleaning, exploratory data analysis, visualization, and machine learning. It demonstrates how Gradient Boosting Regression can be applied to a student performance dataset and how model evaluation helps assess the usefulness and limitations of predictions.

**Dataset Source:** StudentPerformanceFactors.csv — include the original Kaggle dataset URL here.
