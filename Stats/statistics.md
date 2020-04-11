---
title: Statistics
has_children: true
nav_order: 2
---

# Statistics
## Online Courses

- [Introduction to Probability and Statistics](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/index.htm), MIT OpenCourseWare

   This course provides an elementary introduction to probability and statistics with applications. Topics include: basic combinatorics, random variables, probability distributions, Bayesian inference, hypothesis testing, confidence intervals, and linear regression.



## Books covering general topics

- [*Statistical Inference*](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126), Casella and Berger

   A good introduction to graduate level statistics.

- [*Elements of Statistical Learning*](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126), Hastie, Tibshirani, and Friedman

   The textbook showing the rigorous math behind many ML techniques. Available as a free PDF.

- [*Probabilistic Programming and Bayesian Methods for Hackers*](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers), Cam Davidson-Pilon

   A great introduction to Probabilistic programming and bayesian methods, e.g. Monte Carlo, MCMC, etc. lots of examples using PyMC3. Free on github.

## Odds & Ends

- [Common Probability Distributions: The Data Scientist’s Crib Sheet](https://medium.com/@srowen/common-probability-distributions-347e6b945ce4)

   Data scientists have hundreds of probability distributions from which to choose. Where to start? Includes descriptions of the following distributions: Bernoulli and Uniform, Binomial and Hypergeometric, Poisson, Geometric and Negative Binomial, Exponential and Weibull, Normal, Log-Normal, Student’s t, and Chi-squared, Gamma and Beta.

- [Kolmogorov–Smirnov test](https://en.wikipedia.org/wiki/Kolmogorov%E2%80%93Smirnov_test)

   A convenient way to see if samples are from a probability distribution. Can compare one group of samples to a known distribution or a set of 2 samples to each other. Positives: Non-parametric can compare two samples without knowing the underlying distributions. Downsides, 1D distributions only, hard to implement multi dimensional methods.

- [Heteroscedasticity](https://en.wikipedia.org/wiki/Heteroscedasticity) vs [Homoscedasticity](https://en.wikipedia.org/wiki/Homoscedasticity)

   |![alt text](https://raw.githubusercontent.com/pcrumley/ml_stat_resources/master/assets/imgs/Heteroscedasticity.png  "Q9 at the English language Wikipedia / CC BY-SA (http://creativecommons.org/licenses/by-sa/3.0/)") |![alt text](https://raw.githubusercontent.com/pcrumley/ml_stat_resources/master/assets/imgs/Homoscedasticity.png "Q9 at the English language Wikipedia / CC BY-SA (http://creativecommons.org/licenses/by-sa/3.0/)")|

   If the underlying distribution is heteroscedastic it may mess up methods that assume variance is uniform and uncorrelated like goodness of fits in regression problems. For more info, check out this [epsiode](https://open.spotify.com/episode/3CERGsxlO53GdkleMiNLy7) of the Data Skeptic Podcast.

- [FAQ: How are the likelihood ratio, Wald, and Lagrange multiplier (score) tests different and/or similar?](https://stats.idre.ucla.edu/other/mult-pkg/faq/general/faqhow-are-the-likelihood-ratio-wald-and-lagrange-multiplier-score-tests-different-andor-similar/)

   This page introduces the concepts of the a) likelihood ratio test, b) Wald test, and c) score test.
