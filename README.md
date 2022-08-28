# Dimension-Reduction---Singular-Value-Decompo-SVD-
Run SVD on Fashion MNIST data set. Interpret the output and train generative classifiers for multi nomial classification of 10 classes.

Dimension Reduction
Run Singular Value Decomposition (SVD) on
Fashion-MNIST data set, interpret the output and train generative classifiers for multi-
nomial classifiecation of 10 classes. For the Fashion-MNIST data set, you can find more
details in the original GitHub website or Kaggle website.
In this assignment, you are allowed to use a library implementation of SVD. For
python users, we recommend scikit-learn's implementation TruncatedSVD.


Tasks:
Load the training and test data sets from fashion-mnist train.csv and fashion-
mnist test.csv. Each row uses a vector of dimension 784 with values between 0
(black) and 255 (white) on the gray color scale. 

Use SVD to reduce the number of dimensions of the training data set so that it
explains just above 90% of the total variance. Remember to scale the data before
performing SVD. Report how many components you select and their variance
ratios.


Train generative classifiers (Naive Bayes and KNN) and discriminative classifier
(multinomial logistic regression) on both the training data set after SVD and the
original data set (without dimension reduction). Fine-tune the hyper-parameters,
e.g. learning rate in MLR and k value in KNN, to achieve best performance on a
validation set split from the training set. Write a brief description to compare the
performances of these classifiers in terms of accuracy on the test set. 
