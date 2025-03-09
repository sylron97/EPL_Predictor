**EPL Predictor: Forecasting the Outcomes of Premier League Matches for The Premier League Season 2023-2024**

📌 Introduction / Project Overview:

This project is one of the first open-source implementations to predict win, draw, or loss outcomes of English Premier League (EPL) matches using a hybrid approach combining Poisson Regression and Random Forest Regressor. While most football prediction models rely on either statistical methods or machine learning, this project leverages both, enhancing accuracy and offering deeper insights.

Using historical data from 2000-01 to 2022-23, this model forecasts match results, key performance metrics, and final league standings for the 2023-24 EPL season. By making this project open-source, it serves as a valuable resource for football analysts, data scientists, and betting enthusiasts.

🎯 Objective
The primary goal of this project is to develop a prediction model capable of forecasting the outcomes of every EPL match for the 2023-24 season based on historical match data. The model aims to:

✅ Predict Full-Time Result (FTR) – Win, Draw, or Loss

✅ Forecast key match statistics such as Full-Time Goals, Shots on Target, Half-Time Goals

✅ Analyze team performance over an entire season to estimate final league standings

🛠️ Techniques Used:

1️⃣ Poisson Regression Model
Used to predict numerical match statistics, including:
- Full-Time Goals Scored (FTGS)
- Shots On Target
- Half-Time Goals Scored (HTGS)
These features are critical in determining match outcomes.

2️⃣ Random Forest Regressor:
- Used to predict Full-Time Results (Win, Draw, or Loss)
- Incorporates multiple features to improve classification accuracy.

🔥 Tech Stack Used:

📊 Data Processing & Analysis:

- Python – Core programming language for data analysis & model building
- Pandas – Data manipulation and preprocessing
- NumPy – Numerical computations
📈 Statistical & Machine Learning Models:

- Scikit-learn – Implementation of Random Forest Regressor
- Statsmodels – Poisson Regression modeling
📊 Visualization & Reporting:

- Matplotlib & Seaborn – Data visualization for trends and results
- Tableau – Interactive dashboard for match predictions and league standings
📂 Data Storage & Handling:

- CSV Files – Match history dataset storage and processing

📊 Feature Selection Strategy:

To enhance model performance, certain features were removed due to high correlation or redundancy:

🚫 Full-Time Goals Scored (FTGS) – Highly dependent on other features, leading to potential data leakage.

🚫 Half-Time Result (HTR) – Correlated with full-time results, reducing predictive independence.

Feature engineering focused on selecting variables that directly impact match outcomes without introducing biases.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/5bdf5ac1-f566-46bc-a05c-a2107c2f99ed)

✅ Model Evaluation:
The model's performance was evaluated using accuracy, a confusion matrix, and a classification report.

🔹 Accuracy: 64.38% – indicating strong predictive power for match results.

📌 Confusion Matrix: (Image showcasing class-wise predictions)

📌 Classification Report:
![image](https://github.com/sylron97/Python-Projects/assets/132649680/207a1544-a1a8-4e26-8608-5ac045af5d78)

                      precision    recall  f1-score   support

           0 (win)       0.67      0.78      0.72      1254
           1 (draw)      0.43      0.25      0.32       840
           2 (loss)      0.69      0.77      0.73      1266

           accuracy                           0.64      3360
          macro avg       0.60      0.60      0.59      3360
       weighted avg       0.62      0.64      0.62      3360

🔹 Key Observations:

✔ The model predicts wins and losses more effectively than draws, which are harder to forecast due to lower occurrence rates.

✔ Achieved balanced recall and F1-score across classes, ensuring a reliable prediction framework.

📈 Results Analysis:

The model successfully simulated the 2023-24 EPL season, generating key insights:

🔹 Final Standings (Top & Bottom Teams):

🏆 Manchester City secured the highest points, followed by Liverpool and Arsenal.

🔻 Burnley, Sheffield United, and Brentford finished at the bottom.
![image](https://github.com/sylron97/Python-Projects/assets/132649680/e506ee0e-96a9-4425-85f1-d711f488b8f0)

🔹 Win-Loss Distribution:

✔ Manchester City recorded 26 wins, followed by Arsenal and Liverpool with 25 each.

✔ Liverpool finished second due to one additional draw compared to Arsenal.

✔ Burnley had the most losses (28), followed by Sheffield United (27) and Brentford (24).
![image](https://github.com/sylron97/Python-Projects/assets/132649680/29452e9a-ab84-48e0-a1b2-29dd9f076e90)

🔍 Conclusion:

This project is one of the first open-source football analytics models to integrate Poisson Regression and Random Forest for match outcome prediction. By combining statistical and machine learning approaches, the model enhances accuracy and provides a data-driven perspective on EPL match forecasting.

📌 Key Takeaways:

✔ First-of-its-kind open-source hybrid model for football match predictions.

✔ Provides accurate insights into team performance and match results.

✔ Open-source implementation allows for further research and improvements in football analytics, betting models, and AI-driven sports forecasting.

This project serves as a foundation for further development in predictive football analytics. Future improvements could include deep learning models, player-level data integration, and real-time match updates.


