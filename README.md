# **Heart Attack Analysis And Prediction**

## Objective:
The objective of this insight is to use publicly provided patient data to see if we can predict the chances of a heart attack happening. We will use

## Summery Of The Results:

## The Data:
The data provided comes from Kaggle and has 303 rows of patient data. The data set is completely fill out with no null values. It includes metrics like:
- Age
- Sex
- If the get exercise induced angina
- number of major vessels
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- resting ecg
- Max heart rate achieved

## EDA:
The data was already relatively clean and showed normal distribution. Even for a small sample. I didn't remove the outliers since there were very few and the date set was already very small. The class distribution was also relatively even.

## Baseline Model:
For the baseline model, I first scaled the data using **SKLearn's StandardScaler**. After that I trained the data on multiple classifiers to see which one are most accurate. The results were as followed:

                   Logistic Regression: 77.05%
                   K-Nearest Neighbors: 57.38%
                         Decision Tree: 73.77%
                   SVM (Linear Kernel): 77.05%
                      SVM (RBF Kernel): 55.74%
                        Neural Network: 73.77%
                         Random Forest: 77.05%
                     Gradient Boosting: 68.85%
                               XGBoost: 78.69%
                              LightGBM: 75.41%
                              CatBoost: 77.05%

## Final Model:
