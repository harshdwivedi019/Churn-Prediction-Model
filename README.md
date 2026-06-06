**Churn Prediction Model**
This project builds a machine learning model to predict whether a customer will churn (leave) or stay, using their demographic details and service usage data.
It is designed as an end-to-end data science project for learning and portfolio showcasing.

**Table of Contents**
Overview
Datasets
Approach
How TO Run
Future Improvements
Contact

**Overview**
Customer churn is a critical problem for subscription-based businesses such as telecom, banking, and SaaS companies.
The objective of this project is to analyze historical customer data and build a classification model that can predict the likelihood of a customer churning, helping businesses take proactive retention actions.

**Key goals:**

Understand the factors that drive customer churn.

Build a machine learning model to predict churn.

Evaluate model performance using appropriate metrics.

Present insights and recommendations in a clear, interpretable way.

**Dataset**
Source: < Kaggle Telco Customer Churn >

Rows: < 7,043 customers>

Target variable: Churn (Yes/No )

**Approach**
**1**. Data Understanding & Cleaning
Loaded the dataset and checked for missing values, duplicates, and inconsistent entries.
Handled missing data and corrected data types where necessary.
Encoded categorical variables using Label Encoding / One-Hot Encoding.

**2**. Exploratory Data Analysis (EDA)
Calculated overall churn rate.
Analyzed churn across:
Total Charges
Monthly charges and tenure.

Created visualizations using histograms, bar plots, box plots, and correlation heatmaps.

**3.** Feature Engineering
Dropped irrelevant or highly correlated features if needed.
Scaled numerical features for certain models.

**4.** Model Building

Split the dataset into training and test sets.

Trained and compared multiple models, such as:

Logistic Regression

Decision Tree

Random Forest

Tuned hyperparameters using GridSearchCV / RandomizedSearchCV and cross-validation.

6. Insights & Business Recommendations
Identified top features that influence churn (e.g.Total Charges, tenure, monthly charges).

**How To Run**
Clone the repository

bash
git clone https://github.com/harshdwivedi019/Churn-Prediction-Model.git
cd Churn-Prediction-Model
Create and activate a virtual environment (optional but recommended)

bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
Install dependencies

bash
pip install -r requirements.txt
Run the notebook / script

Open the notebook:

bash
jupyter notebook notebooks/churn_analysis.ipynb
Or run the training script:

bash
python src/train_model.py
**Future Improvements**
Deploy the model as a web app (e.g., Streamlit / Flask) for real-time predictions.

Add model explainability using SHAP or LIME to understand individual predictions.

Integrate with a dashboard (Tableau / Power BI) for business users.

Experiment with more advanced models or cost-sensitive learning to better handle class imbalance.

**Contact**
Author: Harsh Dwivedi
GitHub: harshdwivedi019
Location: Lucknow, Uttar Pradesh, India

