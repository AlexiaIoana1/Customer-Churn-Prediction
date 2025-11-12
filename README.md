# Customer-Churn-Prediction

This project demonstrates a complete, end-to-end workflow for predicting customer churn. The process begins with training a machine learning model in Azure Machine Learning Studio and concludes with an interactive, actionable dashboard in Power BI.

Using the Telco Customer Churn dataset, a predictive model was built to classify customers as likely to churn or stay. The model (a Two-Class Decision Forest) was tuned to increase its performance, ultimately achieving an AUC score of 0.805. The predictions from this model were then exported and loaded into Power BI. The resulting dashboard transforms these raw predictions into clear business insights, allowing stakeholders to visualize risk distribution, identify key churn drivers (like contract type and internet service), and instantly access a prioritized list of high-risk customers for the retention team.

Technologies Used: 

- Azure Machine Learning Studio: For data cleaning, model training, and performance evaluation.
- Power BI: For data visualization and building the interactive dashboard.
- Power Query: For cleaning and transforming data within Power BI (e.g., correcting data types).
- DAX: For creating key business metrics (KPIs) in Power BI, such as Actual Churn Rate and High-Risk Customers.
