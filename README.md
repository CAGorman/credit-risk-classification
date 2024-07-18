# credit-risk-classification

## Instructions
The instructions for this Challenge are divided into the following subsections:
  - Split the Data into Training and Testing Sets
  - Create a Logistic Regression Model with the Original Data
  - Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.

### Create a Logistic Regression Model with the Original Data
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
  - Generate a confusion matrix.
  - Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report
1. **An overview of the analysis**: Various techniques were used to train and evaluate a model based on loan risk. Using a dataset of historical lending activity from a peer-to-peer lending services company a model was built 
   that can identify the creditworthiness of borrowers.
   
2. **The results**:
                   precision    recall  f1-score   support

           0       1.00      1.00      1.00     22511
           1       0.87      0.91      0.89       750

    accuracy                           0.99     23261
   macro avg       0.93      0.95      0.94     23261
weighted avg       0.99      0.99      0.99     23261

3. **A summary**jupyter: I would recommend this model.Overall, this model operates with a superb level of success. Class 0 (healthy loan) has perfect scores across the board for precision, recall, & f1-score. Class 1 (high risk loan) 
   performs at a slightly lower rate, but still strong (precision:0.87, recall:0.91, & f1:0.89). Both classes presenting with such high scores, puts the accuracy and weighted avg at 0.99.

### Resources
lending_data.csv was provided in a zip file
