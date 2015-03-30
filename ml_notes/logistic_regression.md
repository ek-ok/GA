## logistic regression

> What data problem does it solve?

- categorical (mostly binary)
- supervised learner

> How do we evaluate performance?

- accuracy: number correct/ number of observations
- correlation,chi^2 test(features)

> What is the output?

probability

> What is interpretable of the algorithm?

coeffiecints(log-odds)
average result given no information( )

> How is it prone to overfitting?

Since any 2 points make a line, and any 3 points make a plane, etc., the more features you have, the more likely the model could become overfit. Polynomials and multicollinearity make that more so.

> How is it customizable?

Regularization: the w parameter represents either the sum (L1) or the squared sum (L2) of the coefficients, while the hyperparameter (`alpha` in sklearn) adjusts the size of that weight

