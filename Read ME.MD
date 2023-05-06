# logistic-regression-model

Logistic regression is a statistical model used to predict binary outcomes, i.e., outcomes that can take on only two values, such as yes/no, true/false, or 0/1. The model uses one or more input features to calculate a probability of the positive outcome (1).

The model is expressed as:

p = 1 / (1 + e^(-z))

where:
- p is the probability of the positive outcome
- z is a linear combination of the input features and their coefficients

z = b0 + b1x1 + b2x2 + ... + bnxn

where:
- x1, x2, ..., xn are the input features
- b0 is the intercept term
- b1, b2, ..., bn are the coefficients for each input feature

The logistic function, also known as the sigmoid function, maps any value of z to a value between 0 and 1, representing the probability of the positive outcome.

Once the model is trained, it can be used to make predictions for new data points by plugging in the values of the input features and calculating the probability of the positive outcome. A threshold can be set to convert the probability into a binary prediction.

Logistic regression is commonly used in binary classification problems, such as predicting whether a customer will buy a product or not, whether an email is spam or not, or whether a patient has a disease or not. It can also be extended to handle multiclass classification problems using techniques such as one-vs-rest or softmax regression.
