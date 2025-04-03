# Housing-price-prediction
This project analyzes the Boston Housing dataset and applies different regression models to predict house prices. The goal is to improve prediction accuracy by handling outliers and testing multiple models.

📌 Steps Followed
Initial Model - Linear Regression

The project starts with a Linear Regression model to establish a baseline for house price prediction.

The initial model’s performance is evaluated using Mean Squared Error (MSE) and R² score.

Handling Outliers

Outliers are identified using the Interquartile Range (IQR) method.

Cleaning the dataset improves model performance by reducing extreme variations.

The improved Linear Regression model achieves a better R² score.

Exploring Advanced Models

After outlier handling, three more models are tested to improve accuracy:

Decision Tree Regressor 🌳

Random Forest Regressor 🌲

XGBoost Regressor 🚀

Each model’s performance is evaluated using the R² score, and the results are compared.

📊 Results

  Model	             R² Score
  
Linear Regression	   0.63

Linear Regression
(After Outlier
Handling)            0.64

Decision Tree	Score  0.87

Random Forest	Score  0.89

XGBoost              0.88	

Best score-0.89

