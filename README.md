🩺 Diabetes Prediction Pipeline
📌 Overview

Built a machine learning pipeline to predict diabetes using patient health data. The project includes outlier handling, scaling, model training, and correlation analysis.

⚙️ Steps
Outlier Treatment: Used IQR method to detect and cap extreme values
Data Split: 70/30 stratified split
Scaling: StandardScaler (fit on train only)
Model: Logistic Regression
Evaluation: Compared train vs test accuracy
Correlation: Checked feature relationships for multicollinearity
📊 Result
Model shows healthy generalisation (train & test accuracy are similar)
No strong multicollinearity observed
🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn

👤 Author

Yash Kadam
