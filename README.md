*DATA SCIENCE INTERNSHIP - TASK 3*
--------
*SKILLCRAFT TECHNOLOGY*
--
🌳 Decision Tree Classifier - Bank Marketing Dataset
--
This project is part of a data analysis internship task focused on building a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit, based on their demographic and behavioral data. The analysis uses the Bank Marketing Dataset from the UCI Machine Learning Repository.

📌 Objective
--
Load and explore the Bank Marketing dataset.
Preprocess the data by handling categorical variables.
Train a Decision Tree Classifier to predict customer subscription.
Evaluate the model using accuracy, confusion matrix, and classification report.
Visualize the decision tree and feature importances.
Derive insights from the decision rules for marketing strategy improvements.

🗃 Dataset Description
---
Source: UCI Machine Learning Repository
Rows: 4521
Target Variable: y (binary: 'yes' / 'no')
Features Include:

age, job, marital, education, balance, housing, loan
contact, day, month, duration, campaign, pdays, previous, poutcome

🛠 Technologies Used
---
Python
Pandas, NumPy
Scikit-learn (DecisionTreeClassifier, LabelEncoder, model selection)
Matplotlib, Seaborn
Jupyter Notebook

🚀 Steps Performed
-----
Data Loading
Loaded CSV using Pandas and explored basic structure and types.

Preprocessing

Handled categorical data using Label Encoding.
Checked for null values and cleaned where necessary.
Model Building

Split dataset using train_test_split.
Trained a DecisionTreeClassifier with entropy criterion.
Limited tree depth to improve interpretability.
Evaluation

Evaluated using accuracy score, confusion matrix, and classification report.
Visualized decision rules and top feature importances.
Visualization

Plotted tree structure using plot_tree (limited to top 3 levels).
Bar plot of feature importances using Seaborn.

📊 Insights
-----
The most influential features were:

duration, poutcome, previous, campaign, balance
The model was interpretable and achieved a reasonable accuracy of X.XX (update this), making it a good baseline model.

Interpretability and simple rules from the decision tree can assist marketing teams in targeting the right customers.

To further improve performance:

Use Random Forests or Gradient Boosting
Apply pruning and hyperparameter tuning
Engineer domain-specific features

📁 Project Structure
--
📦 bank-marketing-decision-tree/ ┣ 📄 bank.csv ┣ 📄 decision_tree_classifier.ipynb ┣ 📄 README.md

📌 Future Work
---
Implement Random Forest and compare results.
Use cross-validation for robust evaluation.
Build an interactive dashboard to visualize predictions.

🙌 Acknowledgements
----
UCI Machine Learning Repository for the dataset.
Scikit-learn documentation for excellent examples and support.

## LINKEDIN:
- https://www.linkedin.com/in/akash-v-9249b2296?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app 

## ## 🎥💻VIDEO :
-
https://www.linkedin.com/posts/akash-v-9249b2296_datascience-sct-task3-activity-7353793210470608897-m9ps?utm_source=share&utm_medium=member_android&rcm=ACoAAEex2awBF83VC-fxl3uuiPf2qnkwSc8A5_0
