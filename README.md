# Lead-Scoring-Case-Study for X Education
Problem Statement - 

Objective
X Education, an online course provider, struggles with a low lead conversion rate (~30%). To optimize the sales process, we aim to develop a logistic regression model to predict lead conversion and assign a lead score (0-100), helping the sales team focus on high-potential leads. The target conversion rate is set at 80%.

Approach - 

1.) Data Cleaning & Preprocessing : Handle missing values and drop irrelevant columns. Replace "Select" in categorical variables as it represents missing data. Convert categorical variables into dummy variables.

2.) Exploratory Data Analysis (EDA) : Identify key factors influencing lead conversion (e.g., lead source, time spent on website, last activity), Visualize trends using bar charts, heatmaps, and histograms.

3.) Model Building : Train a logistic regression model to predict lead conversion, Perform feature selection using RFE (Recursive Feature Elimination), Optimize using grid search for hyperparameters.

4.) Model Evaluation : Confusion matrix, precision, recall, F1-score, and ROC-AUC to assess model performance. Assign lead scores based on predicted probabilities.


