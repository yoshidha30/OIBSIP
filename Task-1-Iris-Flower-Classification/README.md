 🌸 Iris Flower Classification using Machine Learning

📌 Project Overview

The Iris Flower Classification project is a supervised machine learning application that predicts the species of an Iris flower based on its sepal and petal measurements.

This project follows a complete machine learning workflow, including data exploration, visualization, model training, evaluation, and prediction. It was developed as part of a Data Science internship to understand the fundamentals of classification algorithms.



 🎯 Objective

The objective of this project is to build a machine learning model that can accurately classify an Iris flower into one of the following species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

using the flower's measurements.



📂 Dataset Information

The dataset contains "150 flower samples" with the following features:

| Feature       | Description              |
| ------------- | ------------------------ |
| SepalLengthCm | Length of the sepal (cm) |
| SepalWidthCm  | Width of the sepal (cm)  |
| PetalLengthCm | Length of the petal (cm) |
| PetalWidthCm  | Width of the petal (cm)  |
| Species       | Target class             |



🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook (VS Code)



📊 Project Workflow

1. Data Loading

* Imported the Iris dataset using Pandas.
* Displayed the first few records for inspection.

2. Data Exploration

* Checked dataset shape.
* Viewed column information.
* Generated statistical summaries.
* Verified that no missing values were present.

3. Exploratory Data Analysis (EDA)

* Created scatter plots to understand feature relationships.
* Used a pair plot to visualize the distribution of all features across different species.

4. Data Preparation

* Selected input features and target labels.
* Split the dataset into training and testing sets using an 80:20 ratio.

5. Model Training

A **Decision Tree Classifier** was trained using the training dataset to learn patterns from flower measurements.

6. Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

7. Prediction

The trained model was tested on a new flower sample to predict its species.



📈 Results

Model Used: "Decision Tree Classifier"

Accuracy Achieved: "100%"

Classification Report:

* Precision: 1.00
* Recall: 1.00
* F1-Score: 1.00

The confusion matrix showed that all test samples were classified correctly.



🔍 Feature Importance

Feature importance analysis showed that petal measurements contributed the most towards correctly identifying the flower species.



📁 Project Structure

Iris-Flower-Classification-ML/
│
├── Iris.csv
├── iris_flower_classification.ipynb
├── README.md
└── requirements.txt



▶️ How to Run the Project

1. Clone this repository.

   git clone <repository-link>


2. Navigate to the project folder.

   cd Iris-Flower-Classification-ML


3. Install the required libraries.

   pip install -r requirements.txt


4. Open the notebook.

   iris_flower_classification.ipynb

5. Run all cells.



📚 What I Learned

Through this project, I learned how to:

* Load and explore datasets using Pandas.
* Perform Exploratory Data Analysis (EDA).
* Visualize data using Matplotlib and Seaborn.
* Prepare data for machine learning.
* Train a Decision Tree Classification model.
* Evaluate model performance using multiple metrics.
* Predict unseen data using a trained model.
* Document and organize a machine learning project using GitHub.



🚀 Future Improvements

* Compare multiple classification algorithms.
* Perform hyperparameter tuning.
* Deploy the model as a web application.
* Experiment with larger classification datasets.



👨‍💻 Author

M Yoshidha

This project was developed as part of my Data Science learning journey and internship to strengthen my understanding of supervised machine learning and model evaluation.
