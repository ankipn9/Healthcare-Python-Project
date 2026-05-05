Healthcare Analysis: 
This project focuses on analyzing and predicting long hospital stays using healthcare admission data to improve hospital resource planning and patient care. Using a dataset of over 500,000 hospital records, the analysis explores key factors such as severity of illness, department type, admission characteristics, and operational variables that influence patient length of stay. A Logistic Regression model was developed to classify whether a patient is likely to stay more than 10 days at the time of admission. The model achieved strong performance with 96% accuracy and a ROC-AUC score of 0.955, demonstrating high predictive capability. The insights from this project help hospitals optimize bed allocation, improve staffing decisions, and proactively manage high-risk patients, ultimately enhancing operational efficiency and patient outcomes

📊 Project Description 
Built a predictive analytics model to identify patients at risk of long hospital stays (>10 days)
Analyzed a dataset of 500,000+ hospital admission records with clinical and operational variables
Performed data cleaning and preprocessing:
Converted length of stay to numeric
Created binary target variable (long_stay)
Encoded categorical features
Conducted Exploratory Data Analysis (EDA) to identify key drivers:
Severity of illness strongly impacts stay duration
Certain departments (e.g., radiotherapy, anesthesia) have higher long-stay rates
Age and admission deposit show meaningful patterns
Developed a Logistic Regression model for binary classification
Achieved high model performance:
Accuracy: 96.36%
Precision: 96.97%
Recall: 89.16%
ROC-AUC: 0.955
Evaluated model using confusion matrix and ROC curve
Delivered actionable insights for:
Bed management and resource allocation
Staff planning and operational efficiency
Early identification of high-risk patients
