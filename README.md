# Customer-Churn-Prediction
The objective is to build a comprehensive churn prediction and retention system using machine learning techniques on customer behavioral and financial data.

 Problem Statement:-
As an AI/ML enginee,r  your goal is to:

Identify customers likely to churn.

Dataset
The dataset includes anonymized customer records with demographic, financial, and behavioral features. It also includes customer churn labels (0 = Not churned, 1 = Churned).

Project Components
1.  Data Preprocessing
Removed irrelevant/empty columns (customerID, Recommendation)

Handled missing values using:

Mode for categorical variables

Median for numeric variables

Encoded categorical variables using LabelEncoder

Scaled numeric features using StandardScaler

2. Exploratory Data Analysis
Visualized churn distribution

Heatmap to identify feature correlations

3. Predictive Modeling
Built and compared two machine learning models:

Logistic Regression
Accuracy: 79.72%

Precision (Class 1): 58%

Recall (Class 1): 50%

F1 Score (Class 1): 54%

Random Forest Classifier
Accuracy: 83.02%

Precision (Class 1): 69%

Recall (Class 1): 50%

F1 Score (Class 1): 58%

4. Evaluation Metrics
Accuracy

Classification Report

Confusion Matrix

data insights:-
![image](https://github.com/user-attachments/assets/d4ade544-dddf-4b8e-b92b-7648b633e576)
![image](https://github.com/user-attachments/assets/39630890-c750-4af2-ad1f-7b3f0c40c4a1)



