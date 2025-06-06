🚲 Bike Sharing Demand Prediction with AutoGluon

Welcome!
This project leverages AutoGluon, a cutting-edge AutoML framework, to predict hourly bike-sharing demand based on historical data. The goal was to build a high-performing regression model while focusing on rapid experimentation, automated feature engineering, and hyperparameter tuning — all with minimal code.

🔍 Project Overview
✅ Built a baseline model using AutoGluon’s TabularPredictor

🛠️ Engineered new features from the datetime column (e.g., hour, day of week)

🧠 Converted key columns like season and weather into categorical types

🔧 Tuned model hyperparameters to improve performance

📈 Tracked progress through Kaggle scores and visualized improvement

🎯 Goal
Predict the total number of bikes rented (count) using only the features available in the test dataset. The dataset comes from a Kaggle competition and reflects real-world challenges like seasonality, weather, and time-based trends.

🏁 Final Results
📊 Achieved performance improvements across 3 stages:

Baseline → Feature Engineering → Hyperparameter Tuning

📉 Final Kaggle RMSE score: (update with your score)

🤖 Built With
AutoGluon

Python (Pandas, Matplotlib)

Kaggle Dataset: Bike Sharing Demand

🚀 Future Improvements
Add external data (e.g., holiday calendar, weather forecasts)

Use advanced ensembling strategies

Deploy the model as a real-time prediction API
