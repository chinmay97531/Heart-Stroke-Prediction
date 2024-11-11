# Heart Stroke Prediction Using Machine Learning
This project aims to predict the likelihood of a heart stroke based on a set of health-related features using machine learning techniques. Stroke is a major cause of death and 
disability worldwide, and early prediction can help in taking preventive measures to reduce the risks associated with it. This repository includes a complete workflow for data 
preprocessing, feature engineering, model training, and evaluation.

# Project Overview
The project involves:<br>
<strong>Data Preprocessing:</strong> Handling missing values, encoding categorical features, and scaling numerical values to ensure compatibility with machine learning models.<br>
<strong>Feature Engineering:</strong> Identifying and selecting key health metrics that contribute to stroke risk.<br>
<strong>Model Training:</strong> Training various machine learning models (e.g., Random Forest, Logistic Regression, XGBoost) to predict stroke occurrence.<br>
<strong>Model Evaluation:</strong> Assessing model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC to ensure reliable predictions.<br>

# Dataset
The dataset used in this project includes the following features:<br>
<strong>Age:</strong> Age of the individual.<br>
<strong>Hypertension:</strong> Presence of hypertension (0 = No, 1 = Yes).<br>
<strong>Heart Disease:</strong> Presence of heart disease (0 = No, 1 = Yes).<br>
<strong>Ever Married:</strong> Marital status of the individual.<br>
<strong>Work Type:</strong> Type of employment (e.g., Private, Self-employed).<br>
<strong>Residence Type:</strong> Urban or rural residency.<br>
<strong>Average Glucose Level:</strong> Average glucose level in the blood.<br>
<strong>BMI:</strong> Body Mass Index.<br>
<strong>Smoking Status:</strong> Smoking habits of the individual.<br>

# Models and Techniques Used
<strong>Random Forest Classifier:</strong> Used for feature importance and baseline performance.<br>
<strong>Logistic Regression:</strong> For simple yet effective binary classification.<br>
<strong>XGBoost:</strong> An optimized gradient boosting algorithm for higher accuracy.<br>
<strong>Confusion Matrix and Classification Report:</strong> To evaluate model performance in detail.<br>
<strong>Hyperparameter Tuning:</strong> Used to optimize model parameters for improved accuracy.<br>

# Results
The Random Forest Classifier model achieved the highest accuracy, with strong recall and precision scores. Feature importance analysis indicated that variables like age, average 
glucose level, and BMI have the greatest impact on stroke prediction.

# Future Improvements
<strong>Data Augmentation:</strong> To improve model robustness with more diverse data.<br>
<strong>Ensemble Methods:</strong> Combine multiple models to enhance performance.<br>
<strong>Real-time Prediction System:</strong> Build an interactive web application for real-time predictions.<br>

# Getting Started
To run this project locally:<br>
1. Clone the repository.<br>
2. Install dependencies with pip install -r requirements.txt.<br>
3. Run the Jupyter notebook or Python scripts for data analysis and model training.<br>

