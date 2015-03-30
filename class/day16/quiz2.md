1. 
Ordinary Least Squares  (regression)
Logistic Regression (classification)
Naive Bayes (classification)
Decision Trees (regression, classification)
Support Vector Machines (regression, classification)
Nearest Neighbors (regression, classification)
K Means (clustering)
Principal Component Analysis (dimension reduction)

2. 
Given the 4 entities in the matrix above, describe a problem / example we worked on in class for each, and provide one idea on your own.

regression
- solves continuous problems to solve for y
- ex1 predict used car price
- ex2 predict beer rating based on reviews

classification
- solves categorical problems
- ex1 Titanic data, passenger alive or dead
- ex2 classify news categories

clustering
- group similor items together by calculating distance
- ex1 cluster google search text
- ex2 cluster beer reviews

dimension reduction
- reduce matrix dimention to select primary components and to solve multicollinearity issues
- ex1 to predict beer rating use PCA for rating fields such as overall rating, taste, or small. They have multicollinearity issues.
- ex2 predict IQ based on multiple subjects

3. 
All sklearn prediction objects have functions akin to fit(), transform(), predict(), and fit_transform(). Explain each in their most general terms.

fit() - feed matrix into algo
transform() - transform matrix
fit_transform() - does both of the above
predict() - predict based on the trained model

4. 
Two of the above algorithms can use kernels (in their sklearn context) a. Explain what a kernel does b. Which are the two algorithms that use kernels?

karnel - type of hyperparameter that helps to do some calculations faster which otherwise would involve computations in higher dimensional space. 
SVM,  logistic regression

5. One of the above algorithms is most obviously not a linear solution to classification (it does not draw straight decision lines). Which algorithm is it, and how does it decide on decision lines?

Decision Tree
Classify items by creating nodes and trees

6. You are working on microarray (DNA) samples where number of observations (n) is 5 and number of observations (m) is > 10,000.

i. Describe a supervised and unsupervised technique in order to reduce the number of features in the samples to those that are most significant.
supervised: feature selection, using p and f values
unsupervised: PCA

ii. Compare the two techniques in their solution.
PCA is a linear transformation of data

7. Below is a table of Gini Importance (Normalized to 1) in predicting rent in New York City.

i. Decision Tree
ii. Sqft and bedrooms are the two most important features to predict rent

8. What is the Receiving Operator Characteristic Curve? What two metrics is it composed of?

ROC is used along with confusion matrix to evaluate a classifier
True positive rate over false positive reate

9. How does a grid search work? Use an example algorithm from above to help explain it.

Decision tree, use grid search to evaluate the depth for example

10. 
i. What's your strongest "takeaway" from machine learning and this segment of the course?
Got a good undertanding to 4 different types of ML algos and got some practice. I will probably use regression and Kmeans the most for my work.

ii. Given a 2 dimensional figure where y=effort to learn and x=immediate usefulness, and slope = 1, what is one algorithm that felt above the slope (more effort to learn than usefulness) and one algorithm that felt below the slope (more usefulness than effort to learn)?

Nothing! Everything is important!

iii. What's one question you still have about machine learning?
ML evaluation and choosing the best features, algos, hyperparameter tuning.