## KNN

> What data problem does it solve?

Classification (and regression)

> How do we evaluate performance?

- Regression - MSE
- Classification - confusion matrix

> What is the output?

- Distance is calculated across points from features
- class lebels
- The labels are generative -- solved using the datapoints and their labels first

> What is interpretable of the algorithm?

Nothing like coefficient

> How is it prone to overfitting?

- K too big => overfit
- K too small => underfit

> How is it customizable?

- Choose to solve for k
- Distance metric can be changed

## K Means

> What data problem does it solve?

Clustering

> How do we evaluate performance?

- Elbow rule - plot of clusters against % of explained variance. Pick a value of k where majority is explained (left of elbow)
- Trees to understand what clusters represent

> What is the output?

k clusters (every observation is given a cluster)

> What is interpretable of the algorithm?

- k clusters (every observation is given a cluster)
- variance / sum of squares

> How is it prone to overfitting?

- Rule of thumb: k clusters should be < total / 2
- Feature scaling: large variance can account for the majority of the cluster

> How is it customizable?
