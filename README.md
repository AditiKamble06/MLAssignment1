📧 MLAssignment1 – Email Click Prediction for Quantacus.Ai
This repository contains my solution to a case study provided by Quantacus.Ai. The objective is to develop a machine learning model that optimizes email campaigns by predicting which users are most likely to click on links within marketing emails, thereby improving the Click-Through Rate (CTR) and reducing unnecessary email sends.

📝 Problem Statement
The Vice President of Marketing at Quantacus.Ai believes that sending emails randomly to all users is inefficient. The goal is to leverage historical email interaction data to build a predictive model that identifies users with a high probability of clicking on email links. This targeted approach aims to enhance user engagement and optimize marketing efforts.

🔍 Approach
Data Exploration & Cleaning:

Merged datasets to create a comprehensive view of user interactions.

Handled missing values and ensured data consistency.

Feature Engineering:

Created features such as email send time, user engagement metrics, and historical click behavior.

Model Development:

Implemented classification models including Logistic Regression and Naive Bayes.

Addressed class imbalance using techniques like class weighting and threshold tuning.

Model Evaluation:

Evaluated models using metrics such as Precision, Recall, F1-Score, and ROC-AUC.

Focused on optimizing Precision to ensure emails are sent to users most likely to click.

Threshold Tuning:

Adjusted decision thresholds to balance Precision and Recall, aiming for higher CTR.

📈 Results
Achieved a Precision of approximately 17% at a high threshold, indicating that when the model predicts a user will click, it is correct 17% of the time.

This targeted approach significantly improves the CTR compared to random email distribution.

The model effectively reduces the number of unnecessary emails sent, aligning with the marketing team's objectives.
