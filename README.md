# Car-price-prediction
Car Price Prediction is a machine learning project that predicts the selling price of a used car based on features like brand, car age, fuel type, transmission, owner, present price, and kilometers driven. It uses data preprocessing, Random Forest Regression, and evaluation metrics such as RMSE and R² Score to provide accurate price predictions.
Car Price Prediction using Machine Learning
Project Overview
This project predicts the selling price of a used car using Machine Learning. It analyzes various car features such as brand, present price, kilometers driven, fuel type, transmission, owner, and car age to estimate the selling price. The project demonstrates data preprocessing, model training, evaluation, and prediction.
Dataset Used
Dataset: Car Price Prediction Dataset
File Name: car_dataset_dirty_520_rows.csv
Features
Brand
Car_Name
Year
Present_Price
Kms_Driven
Fuel_Type
Transmission
Owner
Target Variable
Selling_Price
Data Preprocessing
The following preprocessing steps were performed:
Removed missing values.
Removed unnecessary column (Car_Name).
Created a new feature Car_Age from the Year column.
Converted categorical variables into numerical values using One-Hot Encoding.
Split the dataset into training and testing sets.
Machine Learning Model Implemented
Algorithm Used:
Random Forest Regressor
Evaluation Metrics:
RMSE (Root Mean Square Error)
R² Score
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Joblib
Steps to Run the Project
1. Install the required libraries
pip install pandas numpy scikit-learn joblib
2. Place the dataset
Copy car_dataset_dirty_520_rows.csv into the project folder.
3. Train the model
Run:
python train_model.py
This trains the model and saves it as:
car_price_model.pkl
4. Run the prediction program
Execute:
python prediction.py
5. Enter the required details
Provide:
Present Price
Kilometers Driven
Previous Owners
Car Age
Brand
Fuel Type
Transmission
The model will predict the estimated selling price of the car.
Project Output
The system displays the predicted selling price of the car based on the user-provided details.
Future Enhancements
Improve prediction accuracy using hyperparameter tuning.
Compare multiple regression algorithms.
Develop a web application using Flask or Streamlit.
Train the model using a larger and more diverse dataset.
