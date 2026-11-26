**CIE-2 ACTIVITY 1
Name : Pushkaraj Mahesh Umbare 
Roll number : AD3371
DIV-C
SUBJECT-RCA**
SUBMISSION LINK- https://github.com/complexiota.

#food delivery prediction model 
Food Delivery Time Prediction using Linear Regression

A Machine Learning project that uses Linear Regression to predict food delivery time in minutes based on distance, weather, traffic conditions, preparation time, vehicle type, and courier experience.

Dataset

"Kaggle – Food Delivery Time Prediction" (https://www.kaggle.com/datasets/denkuznetz/food-delivery-time-prediction)

Technologies Used

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Google Colab.

Model Performance

Evaluation Metric| Score
MAE| 5.3196
MSE| 68.4478
RMSE| 8.2733
R² Score| 0.8325

Methodology

- Data loading and exploration.
- Missing value handling by removing incomplete records.
- Categorical feature encoding using One-Hot Encoding.
- Removed "Order_ID" as it is only an identifier.
- 80:20 train-test split.
- Linear Regression model training.
- Model evaluation using MAE, MSE, RMSE and R².
- Actual vs Predicted visualization and feature coefficient analysis.

Conclusion

The Linear Regression model achieved an R² score of 0.8325, explaining approximately 83.25% of the variation in delivery times. The RMSE of 8.2733 minutes indicates the model's prediction error on unseen test data.

Author

Pushkaraj Umbare

"GitHub Profile" (https://github.com/pushkarajumbare)
