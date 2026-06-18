# 📧 Email Spam Detection using Machine Learning

## 📌 Project Overview

This project predicts whether an email message is "Spam" or "Ham (Not Spam)" using Machine Learning and Natural Language Processing (NLP). The model is trained on labeled email messages and learns to identify spam based on the text content.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, text vectorization, model training, evaluation, and prediction.



## 🎯 Problem Statement

The objective of this project is to build a Machine Learning model that can accurately classify email messages as **Spam** or **Ham** based on their textual content.



## 📂 Dataset Information

The dataset contains email/SMS messages with the following features:

* Category (Spam or Ham)
* Message (Email/SMS Text)



## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* WordCloud
* Joblib
* Jupyter Notebook (VS Code)



## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Inspection
* Missing Value Analysis
* Duplicate Value Analysis
* Spam vs Ham Count Plot
* Pie Chart
* Message Length Distribution
* Box Plot
* Word Cloud Visualization



## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns
* Renamed dataset columns
* Removed duplicate records
* Created **Message_Length** feature
* Converted text into numerical features using **CountVectorizer**



## 🤖 Machine Learning Models

Two classification models were trained and compared:

* Multinomial Naive Bayes
* Logistic Regression

The best-performing model was selected based on classification accuracy.



## 📈 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report



## 📧 Prediction

The trained model was used to classify new email messages as:

* Spam
* Ham (Not Spam)



## 📁 Project Structure


Task-4-Email-Spam-Detection/
│
├── spam.csv
├── email_spam_detection.ipynb
├── spam_detector_model.pkl
├── count_vectorizer.pkl
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

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Natural Language Processing (NLP)
* Text Feature Extraction
* Machine Learning Classification
* Model Evaluation
* Saving Machine Learning Models



## 🔮 Future Scope

Possible improvements include:

* Using TF-IDF Vectorizer
* Training advanced NLP models
* Deploying the model using Streamlit or Flask
* Integrating with real-time email systems



## 👨‍💻 Author

M Yoshidha

This project was developed as part of my Data Science learning journey and Oasis Infobyte Internship to strengthen my understanding of Machine Learning and Natural Language Processing through a real-world spam detection application.
