**MedBuddy Insurance Charges Prediction**
This project aims to predict medical insurance charges based on personal and policy details using machine learning techniques. By analyzing features such as age, gender, BMI, and other factors, the models provide accurate estimates of insurance costs.

Dataset
Personal Details Dataset: Contains demographic and health-related information of policyholders.

Price Dataset: Contains insurance charges associated with policy numbers.

Both datasets are merged for comprehensive analysis.

Features
Data cleaning and preprocessing including label encoding of categorical variables.

Exploratory Data Analysis (EDA) with correlation heatmaps to understand feature relationships.

Feature scaling using StandardScaler.

Multiple regression models implemented: Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting, Support Vector Regressor, and XGBoost.

Model evaluation using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

Visualization of model performances and feature importances.

How to Run
Install the required Python packages listed in requirements.txt.

Load the datasets in the specified Excel format.

Run the provided Jupyter notebook or Python script to train models and view results.

Results
Random Forest and XGBoost models generally showed the best performance in predicting insurance charges.

Feature importance analysis helps identify key factors influencing insurance costs.

Libraries Used
pandas, numpy, matplotlib, seaborn, plotly

scikit-learn, xgboost
