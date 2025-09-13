# CLIENT-POJECT
FicZon Inc Client : Sales Effectiveness | Category: Product Sales Project
Sales Effectiveness Prediction – Client Project
 Project Overview

This project was developed for a client (FicZon Inc) to improve sales effectiveness by leveraging machine learning for lead categorization.

The goal was to automate classification of sales leads into High Potential vs. Low Potential categories, reducing dependency on manual categorization and improving conversion rates.

 Objectives

Perform Exploratory Data Analysis (EDA) to identify sales insights.

Build and evaluate multiple ML models for lead quality prediction.

Provide business recommendations to optimize lead generation and sales strategies.

 Dataset Details

Rows: 7422

Columns: 9

Created (timestamp)

Product_ID

Source

Mobile

Email

Sales_Agent

Location

Delivery_Mode

Status

 Tech Stack

Programming: Python (Jupyter Notebook)

Database: MySQL (project_sales → data table)

Libraries:

Pandas, NumPy (data processing)

Matplotlib, Seaborn (EDA & visualization)

Scikit-learn (ML modeling)

imbalanced-learn (SMOTE for handling imbalance)

 Process Workflow

Data Extraction – pulled data directly from client’s MySQL DB.

Data Cleaning & Preprocessing – handled missing values, categorical encoding, scaling.

EDA:

Lead status distribution (Open, Converted, Lost, Junk Lead, etc.)

Lead sources analysis (Website, Call, CRM forms, etc.)

Sales agent performance comparison.

Time-based lead generation patterns.

Feature Engineering – categorized leads into High Potential (New, Follow-up, Proposal Sent, Negotiation) vs. Low Potential (Lost, Not Interested, Junk).

Modeling – applied classification models:

Logistic Regression

Support Vector Classifier (SVC)

Random Forest

Gradient Boosting

Balanced with SMOTE to fix class imbalance.

Evaluation – accuracy, classification report, confusion matrix.

 Key Insights

Lead Quality: Majority of leads were low-potential, indicating poor targeting.

Lead Sources: Some digital channels generated high volume but low conversions.

Sales Agents: Performance varied significantly — best practices from high-performing agents could be replicated.

Time Trends: Specific months and hours showed higher engagement, suggesting timing impacts conversion.

 Results

Random Forest & Gradient Boosting outperformed other models with higher classification accuracy.

Automated ML categorization reduced dependency on manual sales agent judgment.

Provided clear business insights to improve lead generation channels and sales team effectiveness.
