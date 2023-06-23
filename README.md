# credit-risk-classification


Overview of the Analysis

In this exercise, we applied various techniques to train and evaluate a supervised machine learning model based on loan risk. Using a dataset of historical lending activity, we built a model that can identify the creditworthiness of borrowers by predicting health levels of loans and risk of defaulting.

Factors considered in testing were: loan size, interest rate, borrower income, debt-to-income, number of accounts, derogatory marks, and	total debt. The size of this dataset was 77,536 loans in total.

First we split up the data into features (X variable) and outcome (y variable). Then we split the data into training (80%) and testing (20%) samples. We fit a logistic regression model to get predictions and retrieved its accuracy score. Then we presented a confusion matrix to the model and generated a classification report for overall metrics. Here we see that the logistic regression model does a fairly good job at predicting healthy and high-risk loans. Precision and recall scores are both at a full 100% for the healthy loans outcome, while high risk loan prediction has precision of 87% (the proportion of loans deemed high-rish that was actually correct) and recall of 89% (the proportion of actual high-risk loans that was identified correctly). Accuracy is at 99% so we can draw a conclusion that this model works well in its predictions.

Next we resampled the data to aim for closer predictions. Applying the same method of logistic regression as before, to the resampled data, we see accuracy goes from 99% to 100%. The logistic regression model does an even better job at predicting healthy and high-risk loans when fit with oversampled data. Precision and recall scores both remain at a full 100% for the healthy loans outcome, while high-risk loan prediction has precision of 87% (the proportion of loans deemed high-rish that was actually correct) and recall of 100% (the proportion of actual high-risk loans that was identified correctly). With an accuracy score of 100%, this machine learning model is a strong predictor of loan outcomes for this dataset.
