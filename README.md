# Naive-Bayes-modelling


How do Naive Bayes models work?
A Naive Bayes model is a supervised learning technique used for classification problems. As with all supervised learning techniques, to create a Naive Bayes model you must have a response variable and a set of predictor variables to train the model. 

The Naive Bayes algorithm is based on Bayes’ Theorem, an equation that can be used to calculate the probability of an outcome or class, given the values of predictor variables. This value is known as the posterior probability.

That probability is calculated using three values: 

The probability of the outcome overall P(A)

The probability of the value of the predictor variable P(B)

The conditional probability P(B|A) (Note: P(B|A) is interpreted as the probability of B, given A.)

The probability of the outcome overall, P(A), is multiplied by the conditional probability, P(B|A). This result is then divided by the probability of the predictor variable, P(B), to obtain the posterior probability. 
