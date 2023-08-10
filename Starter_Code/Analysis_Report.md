
Using the data given, I created a logistic regression model to approximate the health of a loan. The model looks at multiple variables, including loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt. The creation of the model entails splitting the data into two groups: training data and testing data. The training data is used to calculate the weights of the variables based on the outcome of the datapoints. The model then takes in the test data and outputs a number that's close to 0 or 1, then rounds to 0 or 1 to show it's prediction.

The Logistic Regression Model:
* The model has an accuracy of 99%. This is dragged down due to the realatively low precision and reall while looking at high-risk loans.
* The Precision of the Logistic Regression Model tells the rate at which a 'positive' prediction corresponds to a case that is actually positive.
  When the model is predicting whether or not a datapoint is high-risk, it has an precision of 89%.
  When the model is predicting whether or not a datapoint is heathy, it's precision goes up to 100%.
* The Recall of athe Logistic Regression Model tells the rate at which 'positive' cases are actually predicted correctly.
  While looking at high-risk loans, the recall is 88%, however when looking at whether a loan is health it's recall jumps to 100%.

Recommendation:
I would only recommend using this model to predict whether or not a loan is healthy. It has perfect results under those conditions. The viability of the model drastically decreases when predicting whether or not a loan is high-risk and would lead you astray in over 10% of cases.