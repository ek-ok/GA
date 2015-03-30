## Naive Bayes

> What data problem does it solve?

categorical , supervised learner (classification)

> How do we evaluate performance?

accuracy: number correct/ number of observations
confusion matrix : false positive, true positive false negative, true negative

> What is the output?

- probability of Y given features
- P(Y|Xn) opposite of logistic regression

> What is interpretable of the algorithm?

- probability of feature showing up given y P(Xn|Y) and P(Y)
- Probability of y is a priori P(Xn)

> How is it prone to overfitting?

- all features are independent of each other -- not as likely to overfit. 
- Does very well with small datasets, predicts very well on larger datasets, but 'coef' tends to be less useful 

> How is it customizable?

- sklearn has an alpha perameter
- Bernoulli or Multnomial
- Bernoulli - presence (matrix of 0's and 1's)
- multinomial - count ( matrix of all numbers)