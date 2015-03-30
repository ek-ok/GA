# Machine Learning Notetaker

Use this notetaker for each algorithm so you can keep track of the important information for each algorithm

## Naive Bayes

> What data problem does it solve?

categorical , supervised learner (classification) or 
continous, supervised 

> How do we evaluate performance?

accuracy: number correct/ number of observations
confusion matrix : false positive, true positive false negative, true negative

> What is the output?

probability of Y given features
P(Y|Xn) opposite of logistic regression

> What is interpretable of the algorithm?

probability of feature showing up given y
P(Xn|Y) 
and P(Y)
Probability of y is a priori
P(Xn)

> How is it prone to overfitting?

all features are independent of each other -- not as likely to overfit. Does very well with small datasets, predicts very well on larger datasets, but 'coef' tends to be less useful 

> How is it customizable?

Kernals,
C 
degrees, or gamma based on kernal

> What is regulation parameter?

C

> What makes SVM better than others:

kernals,
using a subset of data ( support vectors and sparse matrix)
effective in high dimension
still effective in large sample size 

> How does an SVM hyperplane differ from a logistic hyperplane?

Logistic model gets pulled towards new samples, SVM doesn't neccessarily have that