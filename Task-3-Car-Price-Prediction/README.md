# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of used cars using Machine Learning. The model is trained on historical car data containing information such as manufacturing year, present price, kilometers driven, fuel type, seller type, transmission type, and ownership.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and prediction.



## 🎯 Problem Statement

The objective of this project is to build a regression model that can accurately predict the selling price of a used car based on its features.



## 📂 Dataset Information

The dataset contains information about used cars with the following features:

* Car Name
* Manufacturing Year
* Selling Price (Target Variable)
* Present Price
* Kilometers Driven
* Fuel Type
* Selling Type
* Transmission
* Owner



## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib
* Jupyter Notebook (VS Code)



## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset inspection
* Missing value analysis
* Statistical summary
* Correlation heatmap
* Count plots
* Box plots
* Distribution plots
* Feature importance visualization



## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Created a new feature: "Car_Age"
* Removed unnecessary columns
* Encoded categorical variables using One-Hot Encoding
* Split the dataset into training and testing sets



## 🤖 Machine Learning Models

Three regression models were trained and compared:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

The best-performing model was selected based on evaluation metrics.



## 📈 Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

A comparison of all models was performed to select the best one.



## 🚗 Prediction

The trained Random Forest model was used to predict the selling price of a new car based on user-provided features.



## 📁 Project Structure

Car-Price-Prediction-Using-Machine-Learning/
│
├── car data.csv
├── car_price_prediction.ipynb
├── car_price_prediction_model.pkl
├── README.md
├── requirements.txt
└── screenshots/




## 🚀 How to Run

1. Clone the repository.

2. Install the required libraries:
   pip install -r requirements.txt

3. Open the notebook.

4. Run all cells sequentially.



## 📚 Key Learnings

Through this project, I learned:

* Exploratory Data Analysis (EDA)
* Feature Engineering
* One-Hot Encoding
* Regression Algorithms
* Model Evaluation
* Feature Importance Analysis
* Saving trained models
* Organizing Machine Learning projects using GitHub



## 🔮 Future Scope

Possible improvements include:

* Hyperparameter tuning
* Cross-validation
* Deployment using Streamlit or Flask
* Integration with real-world car market data



## 👨‍💻 Author

M Yoshidha

This project was developed as part of my Data Science learning journey and internship to strengthen my understanding of regression models and real-world price prediction problems.
