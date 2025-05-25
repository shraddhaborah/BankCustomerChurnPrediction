# BankCustomerChurnPrediction
Overview
This project presents a complete workflow for predicting customer churn in a retail bank using machine learning techniques. The goal is to identify which customers are likely to leave (churn) so that the bank can take proactive measures to retain them. The notebook covers data exploration, visualization, feature engineering, model building, evaluation, and automated machine learning.

Project Highlights
Data Exploration & Cleaning:
Loaded and cleaned the bank’s customer dataset, removing irrelevant columns and handling categorical variables.

Visualization:
Explored the data with visualizations, including a pie chart showing the proportion of customers who have churned versus those who have been retained.

![Churn Pie Chart

Pie chart: 40% of customers have churned (Exited), while 60% have been retained.

Feature Engineering:
Created new features such as BalanceSalaryRatio and TenureByAge to enhance predictive power.

Preprocessing:
Encoded categorical variables and normalized numerical features for optimal model performance.

Modeling:

Built and trained a neural network using TensorFlow/Keras.

Evaluated model performance using accuracy, confusion matrix, and classification report.

Leveraged H2O AutoML to automatically train and select the best model from multiple algorithms.

Results:
Achieved strong predictive accuracy and identified key features influencing customer churn.

How to Run
Open the Notebook:
Use Google Colab for seamless execution.

Mount Google Drive:
Ensure the dataset (Churn_Modelling.csv) is in your Google Drive and mount it in Colab.

Install Dependencies:
The notebook will prompt you to install any required libraries (e.g., h2o, seaborn).

Run Cells Sequentially:
Follow the notebook from top to bottom to reproduce the analysis and results.

Technologies Used
Python (pandas, numpy, matplotlib, seaborn)

TensorFlow / Keras (for neural network modeling)

scikit-learn (for preprocessing and evaluation)

H2O AutoML (for automated model selection and tuning)

Google Colab (for cloud-based execution)

Key Visualizations
Pie Chart:
Shows the distribution of churned (40%) vs. retained (60%) customers, highlighting the class imbalance in the dataset.

Countplots & Boxplots:
Analyze relationships between churn and various categorical and continuous features.

Next Steps & Improvements
Experiment with additional feature engineering and advanced ensemble models.

Address class imbalance using techniques such as SMOTE or class weighting.

Deploy the best model as a web service for real-time churn prediction.

