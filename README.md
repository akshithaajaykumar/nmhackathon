#nmhackathon
Team BLAZE
NM Hackathon 2025 by GUVI-HCL
INTRODUCTION:
Problem Statement - Predictive Maintenance of Rotating Machinery Using Sensor Data and Machine Learning 
Unexpected machine failures cause costly downtime in manufacturing. Despite having sensor data (vibration, temperature, pressure), most companies use fixed or reactive maintenance schedules.
This project builds a machine learning model to analyze sensor data in real time and predict failures early. It helps reduce downtime, cut maintenance costs, and extend machine life using existing infrastructure.
Data used :
1. Vibration level 
2. Temperature 
3. Pressure 
4. Machine runtime hours
5. Maintenance history
TOOLS USED:
Python,Jupyter Notebook, Pandas, Scikit-learn
STEPS - 
1. We will have to collect data from industries and make it in a type that is readable by the code in the form of an excel.
2. we should collect the required parameters to predict the downtime and to prevent failure beforehand.
3. We should choose the rigth classification or regression model to predict the failure beforehand.
4. We extract data from the file by reading it.
5. We process the data from historical sensors to predict the downtime
6. We develop a Machine Learning model to predict failure in advance 
Classification models used :
1. RandomForest Regresssor
2. Logistic Regression
3. IsolationForest – Anomaly Detection
BUSINESS IMPACT:
1. Lower Maintenance Costs
2. Extended Lifespan
3. Reduced Downtime
4. Improved Safety and Compliance
5. Increased Efficiency of Machines
KEY TAKEAWAYS :
1. Data Preprocessing is Critical 
2. Choosing the Right Model Type
3. Common Errors & Fixes
DataFrame is not callable: Happens when using parentheses `()` instead of brackets `[]` → e.g., `x['col']`, not `x('col')`
Wrong model for the target: Using a classifier on a continuous target causes errors — match model to task type.
4. Confusion Matrix & ROC Curve for Evaluation
Confusion Matrix helps evaluate classification performance (e.g., TP, FP, FN, TN).
ROC Curve shows how well the model distinguishes between classes; AUC closer to 1 = better performance.
CONTRIBUTION TO SOCIETY :
1. Reduces Industrial Waste
2. Lowers Maintenance Costs for All
3. Saves Energy
4. Improves Worker Safety





