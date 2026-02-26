📌 Project Overview

This project applies Machine Learning to solve two real-world business problems across two industries:

Airbnb Listing Price Prediction (Regression)

Telecom Customer Churn Prediction (Classification)

The project follows a structured ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and performance comparison.

It demonstrates practical implementation of regression and classification algorithms using industry-standard evaluation techniques.

🏠 Part 1: Airbnb Price Prediction (Regression Problem)
🎯 Business Objective

To predict Airbnb listing prices based on property features, location factors, and listing characteristics, enabling data-driven pricing decisions.

🔎 Data Preprocessing & EDA

Data cleaning and null value handling

Removal of irrelevant columns

Outlier detection using boxplots

Correlation analysis

Feature selection based on correlation strength

Encoding categorical variables

Train-test split

🤖 Machine Learning Algorithms Used

Linear Regression


📈 Evaluation Metrics

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

These metrics were used to measure prediction accuracy and goodness of fit.

💡 Key Insight

The model was able to capture key relationships between features and listing price. Correlation analysis helped identify strong predictors influencing pricing.

This demonstrates:

Understanding of regression modeling

Proper evaluation of predictive performance

Ability to interpret model outputs

📡 Part 2: Telecom Customer Churn Prediction (Classification Problem)
🎯 Business Objective

To predict whether a telecom customer is likely to churn, allowing proactive retention strategies and reducing revenue loss.

🔎 Data Preprocessing & Feature Engineering

Missing value treatment

Label encoding / One-hot encoding

Feature scaling (StandardScaler / MinMaxScaler as used)

Conversion of categorical variables

Train-test split

🤖 Machine Learning Algorithms Used

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors

Support Vector Machine


📈 Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

The churn model achieved approximately 80% accuracy, indicating reliable classification performance.

💡 Key Insight

Feature scaling improved model performance.

Logistic Regression provided stable and interpretable results.

Precision and Recall analysis helped understand false positives and false negatives.

The model can help telecom companies target high-risk customers for retention campaigns.

🧠 End-to-End ML Workflow Demonstrated

This project demonstrates:

Structured data preprocessing

Feature engineering

Model training and validation

Model comparison

Regression & Classification implementation

Performance evaluation using multiple metrics

Business interpretation of model results

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook
