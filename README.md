📊 Data Science Projects Repository
This repository contains five machine learning projects covering classification, regression, and fraud detection tasks.

📁 Project List
🚢 Titanic Survival Prediction
🎬 Movie Rating Prediction
🌺 Iris Flower Classification
📈 Sales Prediction
💳 Credit Card Fraud Detection
🚢 Titanic Survival Prediction
📌 Objective
Predict whether a passenger survived the Titanic disaster using machine learning.

📊 Dataset
Features: Age, Gender, Ticket Class, Fare, Cabin Info, Embarked Port.
Target: Survived (1) or Not Survived (0).
🔄 Preprocessing
✔ Handle missing values (Age, Fare, Cabin).
✔ Encode categorical features (Sex, Embarked).
✔ Scale numerical features.

🤖 Model Used
Logistic Regression
📈 Evaluation Metrics
Metric	Score
Accuracy	1.0000
Precision	1.0000
Recall	1.0000
F1-score	1.0000
🔗 Notebook: Titanic_Survival_Prediction.ipynb

🎬 Movie Rating Prediction
📌 Objective
Estimate IMDb ratings based on movie attributes.

📊 Dataset
Features: Genre, Director, Cast, Duration, Votes.
Target: IMDb Rating.
🔄 Preprocessing
✔ Handle missing values.
✔ Encode categorical variables.
✔ Convert duration & votes to numeric.

🤖 Model Used
Random Forest Regressor
📈 Evaluation Metrics
Metric	Score
MAE	0.4817
MSE	0.7667
RMSE	0.8756
R² Score	0.2116
🔗 Notebook: Movie_Rating_Prediction.ipynb

🌺 Iris Flower Classification
📌 Objective
Classify iris flowers into Setosa, Versicolor, or Virginica.

📊 Dataset
Features: Sepal & Petal Length/Width.
Target: Iris Species.
🔄 Preprocessing
✔ Handle missing values.
✔ Encode categorical labels.
✔ Normalize feature values.

🤖 Model Used
Logistic Regression
📈 Evaluation Metrics
Metric	Score
Accuracy	1.0000
🔗 Notebook: Iris_Flower_Classification.ipynb

📈 Sales Prediction
📌 Objective
Forecast product sales based on historical data.

📊 Dataset
Features: Advertising Spend, Promotions, Customer Segments.
Target: Sales Figures.
🔄 Preprocessing
✔ Handle missing values.
✔ Feature engineering (trends, seasonality).
✔ Scale numerical features.

🤖 Model Used
Linear Regression
📈 Evaluation Metrics
Metric	Score
R² Score (Test)	99.9999%
R² Score (Train)	99.9999%
🔗 Notebook: Sales_Prediction.ipynb

💳 Credit Card Fraud Detection
📌 Objective
Detect fraudulent transactions efficiently.

📊 Dataset
Features: 28 anonymized transaction attributes + Amount & Time.
Target: Fraud (1) or Legitimate (0).
🚨 Challenge: Class Imbalance
✔ Used SMOTE to balance fraud cases.

🔄 Preprocessing
✔ Scale numerical features.
✔ Address class imbalance.

🤖 Model Used
Random Forest Classifier
📈 Evaluation Metrics
Metric	Score
Accuracy	0.9995
Precision	0.8723
Recall	0.8367
F1-score	0.8542
🔗 Notebook: creditcard.ipynb
