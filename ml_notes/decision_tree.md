## Naive Bayes

> What data problem does it solve?

- classification , supervised learner (classification)
- regression, supervised 

> How do we evaluate performance?

- accuracy: number correct/ number of observations
- confusion matrix : false positive, true positive false negative, true negative
- roc curve: plotting true positive rate over false positive reate

> What is the output?

- regression: y = averages at nodes
- classification: y = purity at each node (probability measure)

> What is interpretable of the algorithm?

- "feature importance": measures information gain normalized to 1
- rule sets: graphviz

> How is it prone to overfitting?

you allow the decision tree to go to far down, allows for to many subsets, which means the training set will be incredibly accurate(even perfect), test set will be significantly worse

> How is it customizable?

- max depth: maximum number of node depth toconsider
- min samples in a split: min has to be 2,but can increase
- max features: how many features to use
- min samples in a leaf: min has to be 2 but ca