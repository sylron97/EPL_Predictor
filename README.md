**EPL Predictor: Forecasting the Outcomes of Premier League Matches for The Premier League Season 2023-2024**

Created a Prediction Model to predict results of every match for the English Premier League Season 2023-2024 with Historical Data used from 2000-2001 Season to 2022-2023 Season.

Regression Models Used.
1. Poisson Regression model used to predict features such as Full time Goals Scored, Shots On Target, Half time Goals Scored, etc basically all the statistically which will not be available to us before the match is played but is important to the result of the match.
2. Random Forrest Regressor used to predict the match result i.e. FTR (Full time Result)

Features That were important to the Random Forrest Regressor Model. Basis on this i decided to remove some features such FTGS and HTR since the model dependent very higly on those features which could skew the result of the model.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/5bdf5ac1-f566-46bc-a05c-a2107c2f99ed)

Below is the confusion matrix of the model as observed from the confusion matrix the Accuracy of the model is 64.375% which is fairly good for predicting future football matches.


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


Results:

Below are the Results of the model. As observed below the team with the most points is Man City followed by Liverpool and Arsenal. The Team with the Least points are Burnley,Sheffiled United and Brentford.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/e506ee0e-96a9-4425-85f1-d711f488b8f0)

Further more anlysis on the same you can see Man City has most wins with 26 followed by Arsenal and Liverpool at 25 since Liverpool has one extra draw compared to Arsenal they come in second in the table. The Team with most lossed is Burnley at 28 losses followed by Sheffiled United at 27 and Brentford at 24.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/29452e9a-ab84-48e0-a1b2-29dd9f076e90)



