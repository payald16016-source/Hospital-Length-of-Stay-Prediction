 **Project Overview**

Optimizing resource management and bed availability is a critical challenge for healthcare providers. This project leverages Machine Learning to predict the duration of a patient's stay (Length of Stay) based on various factors such as patient demographics, admission details, and hospital resource statistics.

The objective is to provide actionable insights that help hospitals schedule staff and manage patient inflow more effectively.

 **Tech Stack & Tools**
Programming Language: Python
Data Manipulation: Pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Machine Learning: XGBoost, Random Forest, Scikit-learn
Environment: Jupyter Notebook

 **Key Highlights & Workflow**
1. Data Preprocessing & Cleaning
Missing Value Imputation: Handled null values in features like Bed_Grade and City_Code_Patient using statistical mode imputation to maintain data integrity.
Feature Selection: Dropped irrelevant identifiers (case_id, patientid) to prevent model noise and focus on predictive features.

2. Feature Engineering
Categorical Encoding: Applied Label Encoding to transform qualitative features (e.g., Severity of Illness, Age, Department) into a machine-readable format.
Data Splitting: Partitioned the dataset into 80% training and 20% testing sets to ensure robust model evaluation.

3. Exploratory Data Analysis (EDA)
Conducted bivariate analysis to understand the correlation between illness severity and stay duration.
Visualized patient distribution across age groups and hospital departments using Seaborn.

4. Model Training & Comparison
Evaluated multiple classification algorithms to determine the most reliable predictor:
Decision Tree: Baseline model.
Random Forest: Ensemble approach for better generalization.
XGBoost: Gradient boosting method for optimized performance.

 **Results & Performance**
The XGBoost Classifier emerged as the top-performing model, achieving an accuracy of 42.66%. While the dataset is inherently complex and skewed, the model provides a significant improvement over baseline methods and successfully identifies key stay patterns.

 **Future Scope**
Implementing SMOTE to handle class imbalance in target categories.
Performing Hyperparameter Tuning via GridSearchCV to further boost accuracy.
Integrating real-time patient history for more personalized predictions.
