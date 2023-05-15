# Capstone-Health-Care-Project---ML-Tableau-Dashboard


The code provided appears to be an analysis of a health care dataset related to diabetes. Here is a breakdown of what the code does:

1. Import necessary libraries: The code begins by importing the required libraries, including `numpy`, `pandas`, `matplotlib`, `seaborn`, and `style` from `matplotlib`.

2. Read the dataset: The code reads a CSV file named 'health_care_diabetes_raw.csv' using the `pd.read_csv()` function and assigns it to the variable `data`.

3. Data exploration and missing values treatment: The code performs various exploratory tasks on the dataset, including checking for null values, identifying missing values in specific columns (Glucose, BloodPressure, SkinThickness, Insulin, BMI), and visualizing the distributions of those columns using histograms. It calculates the percentage of missing values in each column and decides to replace the missing values with the mean values of SkinThickness and Insulin columns.

4. Correlation analysis and scatter plots: The code generates pair plots to visualize the relationships between different variables in the dataset. It also computes the correlation matrix and creates a heatmap to visualize the correlation between variables.

5. Data modeling and model performance evaluation: The code builds and evaluates several machine learning models using different algorithms. It includes the following models:

   a) Logistic Regression: The code trains a logistic regression model, calculates its accuracy on the training and test sets, and generates a confusion matrix, classification report, and receiver operating characteristic (ROC) curve.

   b) Decision Tree Classifier: The code tunes the hyperparameter `max_depth` for a decision tree classifier using a loop, selects the optimal value, and builds a decision tree model. It evaluates the model's accuracy, generates a confusion matrix, classification report, precision and recall scores, and an ROC curve.

   c) Random Forest Classifier: The code trains a random forest classifier, tunes the hyperparameter `n_estimators` using a loop, selects the optimal value, evaluates the model's accuracy, generates a confusion matrix, classification report, precision and recall scores, and an ROC curve.

   d) Support Vector Machine (SVM): The code builds an SVM model with a radial basis function kernel and evaluates its accuracy on the training and test sets.

   e) KNN Classifier: The code builds a K-nearest neighbors (KNN) classifier, evaluates its accuracy on the training and test sets, and generates an ROC curve.

   The code also includes the generation of precision-recall curves for the logistic regression model.

Overall, this code performs data exploration, missing value treatment, correlation analysis, and evaluates multiple machine learning models for diabetes prediction based on the provided dataset.




Tableau Dashboard
Created a Tableau Dashboard for the same dataset to 
