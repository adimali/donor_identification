# This is the repo for doner identification project.

In this project, I employ several supervised learning algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. Then the best algorithm was chosen for further optimization. The dataset for this project originates from the UCI Machine Learning Repository. The datset was donated by Ron Kohavi and Barry Becker, after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid".

GradientBoostingClassifier was selected based on the Accuracy, F-Score and runtime. Compared to the Benchmark Predictor, Optimized GradientBoostingClassifier model has a great improvement in both Accuracy (0.2478 -> 0.8668) and F-Score (0.2917 -> 0.7455). After the parameter optimization it is found that setting minimum samples per leaf as 5 and number of estimators as 200 further improves both Accuracy and F-score to 0.8705 and 0.7523 respectively.
## Creators

* Adimali Piyadasa
    - [https://adimali.github.io/](https://adimali.github.io/)
