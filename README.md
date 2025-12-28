# Student Performance Prediction

This project focuses on predicting student academic success using a dataset of students in a Portuguese course. It implements data cleaning, exploratory data analysis (EDA), and machine learning classification to identify whether a student will pass or fail based on various socio-economic and academic features.

## 📊 Project Overview
- **Data Preprocessing:** Handled semicolon-separated raw data and converted final grades (G3) into binary classification (Pass/Fail).
- **Exploratory Data Analysis:** Visualized correlations and distributions using Seaborn and Matplotlib.
- **Machine Learning:** Trained a classifier to predict student outcomes.
- **Evaluation:** Performance is measured using a Confusion Matrix and ROC-AUC curves.

## 🛠️ Requirements
The project is built using Python 3 and the following libraries:
- `pandas`: For data manipulation.
- `scikit-learn`: For machine learning and model evaluation.
- `seaborn` & `matplotlib`: For data visualization.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/MinaMehdipoor/Student-Churn-prediction.git](https://github.com/MinaMehdipoor/Student-Churn-prediction.git)

2. Navigate to the project directory:
   ```bash
   cd Student-Churn-prediction
   
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb

## 🧪 Results
- The model's performance is visualized through Matplotlib and Seaborn, providing insights into:
- Feature importance.
- Trade-offs between True Positive and False Positive rates (ROC Analysis).
- Detailed classification reports (Accuracy, F1-Score, etc.).
