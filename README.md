# churn-prediction-ml
This project predicts customer churn using machine learning models (Logistic Regression, Random Forest, XGBoost). Includes dataset preprocessing, model training, performance evaluation with metrics, and insights into customer behavior.

# Dataset Description
- Source: [Dataset Link](https://your-dataset-link.com)  
- Features: Features (Key Columns):
  * gender: Customer’s gender (Male/Female)
  * SeniorCitizen: Senior citizen status (1 = Yes, 0 = No)
  * Partner, Dependents: Whether the customer has a partner or dependents
  * tenure: Months with the company
  * PhoneService, MultipleLines: Phone service details
  * InternetService: DSL, Fiber optic, or None
  * OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies: Additional subscribed services
  * Contract: Month-to-month, One year, Two year
  * PaperlessBilling: Paperless billing status
  * PaymentMethod: Payment method type
  * MonthlyCharges, TotalCharges: Monthly and total billing amounts
- Target:
  Churn: Whether the customer discontinued the service (Yes = churned, No = retained).

# Steps Taken
1. Data cleaning & preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering  
4. Model building (e.g., Logistic Regression, Random Forest, XG Boost etc.)  
5. Model evaluation

# Results & Insights
- Logistic Regression achieved **0.802% accuracy / 0.591 F1 score**.  
- Customer tenure and contract type play a crucial role in churn prediction.
  * Key Insights:
    - Overall churn rate is 27%, with most churn concentrated among new customers.
    - Customers with short tenure (<12 months) and high monthly charges are the most likely to churn.
    - Customers with high total charges (long-term, loyal customers) show much lower churn rates.
    - This indicates that the first few months are critical in customer retention.
  * Business Implication:
    Focus on **early retention strategies** such as onboarding offers, discounts, or loyalty programs for high-value new customers to reduce churn and  maximize lifetime value.
- 
