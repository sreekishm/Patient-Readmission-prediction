# Patient-Readmission-prediction
End-to-end healthcare analytics project using the Heritage Health Prize dataset. Covers data cleaning, feature engineering, and predictive modeling to forecast Year-2 hospital admissions and length of stay using Random Forest classification and regression models.
# Overview
This project applies advanced business analytics on the Heritage Health Prize dataset to predict patient hospital readmission and length of stay. The goal is to support efficient healthcare resource planning using data-driven insights.
# Dataset
The dataset consists of multiple relational tables including Claims, Members, Lab Counts, Drug Counts, and Days in Hospital, containing both numerical and categorical healthcare features.
# Methodology
- **Data Cleaning**: Handling missing values, removing pseudonymous identifiers, and filtering relevant records
- **Data Transformation**: Converting range-based and text-formatted variables into numerical values
- **Feature Engineering**: One-hot encoding categorical features and handling capped values (e.g., 80+, 7+)
- **Target Creation**:
   - Binary classification for Year-2 hospital admission
   - Binary classification for Year-2 hospital admission
 # Model Used
 - RandomForestClassifier for hospital admission prediction
 - RandomForestRegressor for length-of-stay prediction
# Results
- Classification Accuracy: 84.03%
- Regression Performance: R² = 31.73%, MAE = 0.779
# Tools and Technology Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
# Outcome
The project demonstrates how predictive modeling can enhance hospital efficiency by anticipating patient inflow and resource requirements.
