# End-to-End Bulldozer Price Prediction

This project predicts the future sale price of bulldozers based on historical sales data.

📊 Dataset

The data is from the Kaggle Bluebook for Bulldozers competition
.
It contains over 400,000 sales records with 50+ features including machine type, usage, year made, and sale date.

🧠 Approach

1. Problem Definition
Predict bulldozer sale price given its features.

2. Data Preparation

Parsed saledate into year, month, day, etc.

Handled missing values

Converted categorical variables into ordered categories

3. Modeling

Trained a RandomForestRegressor

Used feature importance to understand model predictions

4. Evaluation

Used RMSLE (Root Mean Squared Log Error) as per competition rules

Validated on a hold-out set (2012 Q1-Q2 data)

🛠️ Tech Stack

Python

Pandas, NumPy, Matplotlib

Scikit-learn

🚀 Results

Built a regression model capable of predicting bulldozer prices with reasonable RMSLE, following Kaggle competition methodology.
