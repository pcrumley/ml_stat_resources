---
title: Some Standard Methods
has_children: False
parent: Machine Learning
nav_order: 1
---

## Gaussian Naive Bayes Classifier

- [Gaussian Naive Bayes Classifier: Iris data set](https://xavierbourretsicotte.github.io/Naive_Bayes_Classifier.html)

   Nice write-up of applying the sklearn Naive_Bayes_Classifier to the Iris dataset.

## Linear Methods

- [PyData talk: Winning with Simple, even Linear, Models](https://www.youtube.com/watch?v=68ABAU_V8qI)

   Great talk about how to get a lot of mileage with tricks using logistic and linear regression.

- [Solving least squares by Matrix inversion](https://mathworld.wolfram.com/LeastSquaresFitting.html)

   Most ML libraries find the minima of e.g. a linear or logistic regression by means of gradient descent. However, you can find the minimum exactly by solving what is called in Linear algebra a [Normal Equation]()
## Regularization

- [Ridge vs LASSO](https://www.astroml.org/book_figures/chapter8/fig_lasso_ridge.html)

   A nice plot giving intuition why Ridge ([*L<sup>2</sup>*](https://en.wikipedia.org/wiki/Lp_space#The_p-norm_in_finite_dimensions)) regularization tries to make parameters to be small whereas LASSO ([*L<sup>1</sup>*](https://en.wikipedia.org/wiki/Lp_space#The_p-norm_in_finite_dimensions)) regularization tends to force some parameters towards zero, while others can stay large.


## Encoding Data for ML Models

- [Smarter Ways to Encode Categorical Data for Machine Learning](https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine-learning-part-1-of-3-6dca2f71b159)

    Better encoding of categorical data can mean better model performance. In this article I’ll introduce you to a wide range of encoding options from the [Category Encoders](http://contrib.scikit-learn.org/categorical-encoding/index.html) package for use with scikit-learn machine learning in Python.


## Dimensionality reduction

- [Singular Value Decomposition](https://www.youtube.com/watch?v=P5mlg91as1c)

   Good clear video explaining SVD from a Stanford AI course. (*13 minutes*)

- [StatQuest: Principal Component Analysis (PCA), Step-by-Step](https://www.youtube.com/watch?v=FgakZw6K1QQ)

   YouTube video showing how to use SVD to perform PCA. (*21 minutes*)
