# Telecom Customer Churn Prediction 📊

## Overview
This project predicts whether a telecom customer will churn (leave the company) based on service usage and demographic data.  
Goal: Help telecom companies identify at-risk customers and improve retention strategies.

## Dataset
- Source: upload on github
- Total Rows: 7,043  
- Total Columns: 21  
- Target: `Churn`

## Workflow
1. **Data Cleaning**
   - Fixed missing values in `TotalCharges`
   - Handled rows with zero tenure
2. **Exploratory Data Analysis**
   - Visualized churn by gender, contract type, payment method, and internet service
3. **Feature Engineering**
   - Encoded categorical variables (Label + One-Hot Encoding)
   - Scaled numerical features using StandardScaler
4. **Modeling**
   - Trained models:
     - Logistic Regression
     - Random Forest
     - Decision Tree
     - Gradient Boosting
     - SVC
   - Compared performance metrics
5. **Evaluation**
   - Accuracy, confusion matrix, and classification report

## Key Insights
- Customers with **month-to-month contracts** had ~75% churn rate.  
- **Electronic check** payment users were most likely to churn.  
- **Long-term contracts** and **automatic payments** reduced churn significantly.

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn, Plotly  

## Results
Built a predictive model that helps identify customers at high risk of churn, enabling proactive retention strategies.

## Author
**Waqar Ali**  
📍 Karachi, Pakistan  
📧 [waqarnaich83@gmail.com](mailto:waqarnaich83@gmail.com)
