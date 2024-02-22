**EPL Predictor: Forecasting the Outcomes of Premier League Matches for The Premier League Season 2023-2024**

Created a Prediction Model to predict results of every match for the English Premier League Season 2023-2024 with Historical Data used from 2000-2001 Season to 2022-2023 Season.

Techniques Used:
Utilized Regression Models:
1.Poisson Regression Model: Predicted features such as Full-time Goals Scored, Shots On Target, Half-time Goals Scored, etc., crucial for determining match outcomes.
2.Random Forest Regressor: Predicted the Full-time Result (FTR) of matches.

Feature Selection Strategy:
Identified and removed features such as Full-time Goals Scored (FTGS) and Half-time Result (HTR) which exhibited high dependency, potentially skewing the model's predictions.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/5bdf5ac1-f566-46bc-a05c-a2107c2f99ed)

Model Evaluation:
Achieved an accuracy of 64.375% as observed from the confusion matrix, indicating a satisfactory performance in predicting future football match results.
Confusion Matrix:
![image](https://github.com/sylron97/Python-Projects/assets/132649680/207a1544-a1a8-4e26-8608-5ac045af5d78)

Below is the Classification Report

Classification Report:
              precision    recall  f1-score   support

           0       0.67      0.78      0.72      1254
           1       0.43      0.25      0.32       840
           2       0.69      0.77      0.73      1266

    accuracy                           0.64      3360
   macro avg       0.60      0.60      0.59      3360
weighted avg       0.62      0.64      0.62      3360


Results Analysis:
1.The model's predictions revealed that Manchester City secured the highest points, followed by Liverpool and Arsenal. Conversely, Burnley, Sheffield United, and Brentford attained the least points.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/e506ee0e-96a9-4425-85f1-d711f488b8f0)

2.Manchester City led with 26 wins, closely trailed by Arsenal and Liverpool with 25 wins each. Liverpool secured the second position due to one additional draw compared to Arsenal.
Burnley suffered the most losses (28), followed by Sheffield United (27) and Brentford (24).
![image](https://github.com/sylron97/Python-Projects/assets/132649680/29452e9a-ab84-48e0-a1b2-29dd9f076e90)

Conclusion:
The project demonstrated proficiency in utilizing regression models for predictive analysis, yielding insights into team performance and match outcomes in the English Premier League.
This structured presentation highlights the key aspects of your project, from the objective and techniques used to the evaluation metrics and results analysis, providing a comprehensive overview for potential employers.



