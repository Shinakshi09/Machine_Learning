# Consumer-Categorization-based-on-Family-Income
Project Scope
  1. Project is aimed at categorizing consumers into two different classes
  2. Annual Income is the Response Variable.
  3. Consumers to be categorized either Below Average Income or Above Average Income based on Annual Income
  4. Data set has 13 variables and 5351 records
  5. Project time line is 14 calendar days
  6. Application of multiple techniques to access best model

Project Execution
  1. Understanding variable and correlation within variable is first step
  2. Data analysis and cleaning is important task to determine encoding technique, null value replacement
  3. Variable have been converted to numeric type using Label encoding
  4. Null values have been replaced with NaN.
  5. Heatmap and Correlation Matrix shows high correlation between
  6. No of Earning Members in the Family and Annual Income
  7. Train and Test data ratio is kept at 80:20
  
Six different classification techniques have been used
  1. Naïve Bayes
  2. Decision Tree
  3. Logistic Regression
  4. KNN
  5. Support Vector Machine
  6. Random Forest
  
Mode Prediction Accuracy, Confusion Matrix and AUC Ratio have been considered as criteria to judge best model

Best Model
  1. KNN and Naïve Bayes has Less Prediction Accuracy and AUC Ratio
  2. SVM model has high Prediction Accuracy of 88.04 % but has low AUC ratio of only 72%
  3. Random Forest, KNN, Logistic Regression, Decision Tree all show nearby same accuracy and AUC Ratio
  4. Logistic Regression has second highest number of correctly classified records but better AUC ratio, hence Logistic Regression Model is chosen as best model amongst      all the models.
