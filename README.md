# Donors-Choose-GBDT-Analysis-with-Response-Coding

## Overview
This project involves working with gradient boosting decision trees (GBDT) and response coding for a classification task. The primary goal is to use GBDT to predict whether projects on Donors Choose will be approved. You'll explore various feature sets, perform hyperparameter tuning, visualize the results, and summarize your findings.

## Tasks Completed
1. Applied GBDT on two different feature sets:
   - Set 1: Used response coding for categorical features, numerical features, project_title (TFIDF), and preprocessed_essay (TFIDF).
   - Set 2: Used response coding for categorical features, numerical features, project_title (TFIDF W2V), and preprocessed_essay (TFIDF W2V).

2. Performed hyperparameter tuning to find the best hyperparameters for GBDT using k-fold cross-validation. You explored hyperparameters like n_estimators and max_depth.

3. Represented the results through visualizations, such as 3D scatter plots and heatmaps to observe the model's performance concerning different hyperparameters.

4. Evaluated the model's performance on the test data, including AUC and ROC curve. Also, calculated and visualized the confusion matrix.

5. Summarized the project results, presenting key findings in a table format.

For more details, you can refer to the project's Jupyter Notebook.

