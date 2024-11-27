# Customer Churn Prediction Dashboard

## Overview

The **Customer Churn Prediction Dashboard** is designed to help banks and financial institutions predict the likelihood of customers churning (leaving). This dashboard uses multiple machine learning models to provide actionable insights, helping businesses retain their valuable clients.

---

## Key Features

- **Customer Data Input**  
  Input customer details such as credit score, location, gender, age, tenure, balance, number of products, and more.

- **Machine Learning Models**  
  Predict churn probability using:
  - XGBoost
  - Random Forest
  - K-Nearest Neighbors
  - Decision Tree
  - Support Vector Machine (SVM)
  - Voting Classifier

- **Visualizations**  
  Dynamic gauge charts and bar plots visualize churn probability across different models.

- **Personalized Insights**  
  Human-readable explanations of the top factors contributing to churn risk.

- **Email Recommendations**  
  Automatically generate personalized emails to engage at-risk customers with retention incentives.

---

## How It Works

1. **Data Input**  
   Select a customer from the dataset or manually input customer details.

2. **Churn Prediction**  
   Predict churn likelihood using machine learning models and display the probabilities.

3. **Insight Generation**  
   Generate natural-language explanations for the top factors influencing churn.

4. **Customer Engagement**  
   Create personalized emails with tailored incentives to retain customers.

---

## Technologies Used

- **Backend & Machine Learning**
  - Python
  - XGBoost, Random Forest, SVM, KNN, etc.
  - SMOTE for handling imbalanced datasets

- **Frontend**
  - Streamlit for the interactive dashboard

- **Visualization**
  - Plotly for dynamic charts

- **AI Assistance**
  - OpenAI’s LLMs for natural language explanations and email generation

---

## Why This Matters

**Customer churn prevention** is critical in the competitive banking industry. By identifying at-risk customers early and offering personalized incentives, businesses can boost customer retention, increase revenue, and build long-term loyalty.

---

## How to Use

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   cd <repository_folder>
