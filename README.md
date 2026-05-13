Hospital Length of Stay (LOS) Prediction

 Project Overview
Hospital resources manage karne ke liye stay duration predict karna ek critical task hai. Is project ka goal hai patient aur hospital features ka use karke ye predict karna ki patient kitne din hospital mein rahega.

 Tools & Technologies
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Algorithms: XGBoost Classifier, Random Forest, Decision Tree
IDE: Jupyter Notebook

 Key Steps
Data Cleaning: Handled missing values in Bed_Grade and City_Code_Patient using mode imputation.
Feature Engineering: Implemented Label Encoding for categorical variables like Age and Severity of Illness.
Exploratory Data Analysis (EDA): Visualized stay duration patterns across different age groups and illness severities.
Model Building: Trained multiple models and optimized hyperparameters for better performance.

 Results
Best Model: XGBoost Classifier
Final Accuracy: 42.66%
The model effectively handles non-linear relationships and provides insights into patient stay patterns.
