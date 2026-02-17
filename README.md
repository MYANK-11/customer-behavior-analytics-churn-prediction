# Customer Behavior Analytics & Churn Prediction

### End-to-End Data Analytics and Machine Learning Pipeline

This project analyzes retail customer purchasing behavior and develops a predictive churn model using behavioral feature engineering and machine learning. It demonstrates a complete data workflow spanning SQL analytics, statistical exploration, predictive modeling, and business visualization to support customer retention and marketing strategy decisions..



### Business Problem
A retail company aims to understand customer purchasing behavior and proactively identify churn-risk customers to improve retention, engagement, and revenue optimization. The objective is to analyze demographic and behavioral purchase patterns, uncover key drivers of customer loyalty, and develop predictive signals that enable targeted marketing and customer retention strategies.



### Dataset

    • 3,900 retail customers

    • Demographics, purchase behavior, subscription, and spending attributes

    • Aggregated customer-level transactional features


## Analytics Phase (Data Analyst)

Exploratory and SQL-based analysis was conducted to evaluate:

   • revenue distribution and spending patterns

   • customer segmentation by demographics and product category

   • purchase frequency and subscription behavior

   • promotion and discount dependency

   • cohort-level engagement trends

Insights were delivered through interactive Power BI dashboards highlighting revenue drivers, customer segments, and retention-risk indicators.



## Machine Learning Phase (Data Scientist)

A predictive churn model was developed using engineered behavioral features and a multi-factor churn definition aligned with real retail disengagement patterns.

### Target Engineering

Churn was defined using behavioral disengagement signals:
  
    • low purchase frequency

    • low purchase history

    • lack of subscription

    • low spending

    Customers meeting ≥2 conditions were labeled churn-risk.



### Feature Engineering

Behavioral predictors included:

    • purchase history tiers

    • subscription status

    • spending level

    • demographic and category features

    • promotion and discount usage

Categorical variables were one-hot encoded and numeric features imputed using median strategy to ensure modeling integrity.


### Model Training & Evaluation

Models were trained using scikit-learn pipelines:

    • Logistic Regression

    • Random Forest

Evaluation metrics:

    • Accuracy

    • ROC-AUC
  
### Model Performance

    • Logistic Regression — Accuracy 80.5%, ROC-AUC 0.91

    • Random Forest — Accuracy 79.0%, ROC-AUC 0.91

Behavioral target engineering improved ROC-AUC from ~0.53 (frequency-only baseline) to 0.91, demonstrating the impact of engagement-based churn definition on predictive performance.



### Key Churn Drivers

Model interpretability identified primary churn signals:

    • low purchase history

    • lack of subscription

    • behavioral engagement level


These drivers align with real-world retail retention patterns and provide actionable targeting insights.

### Business Impact

The project demonstrates how combining analytics and machine learning enables:

    • identification of high-risk customer segments

    • retention targeting signals

    • behavioral engagement scoring

    • data-driven marketing prioritization


### Project Deliverables

The project delivers an end-to-end analytics and machine learning solution spanning descriptive analysis, predictive modeling, and business insight delivery.


<img width="2736" height="2799" alt="Deliverables" src="https://github.com/user-attachments/assets/a2b846e4-25c2-467d-922c-cebf441ebcba" />


### Tech Stack

<img width="2376" height="2172" alt="tech stack" src="https://github.com/user-attachments/assets/50b182fd-cdae-483a-9da1-b4afa503e930" />



<!--# Project Structure-->



### Why This Project Matters

This project showcases the integration of data analytics and machine learning to transform customer behavior data into predictive retention insights. It reflects real industry workflows where exploratory analysis, statistical reasoning, and predictive modeling combine to support business decision-making.






<!--
## 📌 Author

MAYANK P. SAVANI 

Aspiring Data Analyst | SQL | Python | Power BI
