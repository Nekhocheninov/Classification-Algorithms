# Python AdaBoost & GradientBoosting

[![Open in Colab](https://img.shields.io/badge/Open%20in%20Colab-Open-blue?logo=google-colab)](https://drive.google.com/file/d/1AWzhl1zzAxBtrjhhlR2JByf-zJQhDsXO/view?usp=sharing)

Implementation of classification algorithms [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost) and [Gradient boosting](https://en.wikipedia.org/wiki/Gradient_boosting) in Python.

## Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/1AWzhl1zzAxBtrjhhlR2JByf-zJQhDsXO/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

## Samples

### Dataset

The training and testing datasets were taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/), using the [Wine Dataset](https://archive.ics.uci.edu/dataset/109/wine).

These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

### Analysis

Classification accuracy for different values n_estimators:

| n_estimators |	AdaBoost |	Gradient Boosting |
|---|---|---|
| 10 |	0.907407 |	0.944444 |
| 50 |	0.925926* | 0.981481 |
| 100 |	0.925926 |	1.000000 |
| 200 |	0.925926 |	1.000000 |
| 500 |	0.925926 |	1.000000 |
| 1000 |	0.925926 |	1.000000 |

<img src="https://github.com/Nekhocheninov/Classification-And-Regression-Algorithms/blob/main/AdaBoost%26GradientBoosting/img/img_1.PNG" width="500">

Based on the table and figure, we can conclude that the optimal value for AdaBoost and Gradient Boosting is 50 and 100; with these values, both algorithms achieve maximum accuracy.

Let's check the stability of the algorithms:

| Train size |	Test size |	AB correct |	AB incorrect |	GB correct |	GB incorrect |
|---|---|---|---|---|---|
|104	|54	|50	|4	|54	|0|
|84	|54	|47	|7	|52	|2|
|54	|54	|31	|23	|47	|7|

As can be seen from the table, the gradient boosting algorithm is more stable and maintains high classification accuracy with small training set sizes.

### Conclusion

AdaBoost tends to increase the weights of incorrectly classified samples and decrease the weights of correctly classified samples, allowing the base models to focus on samples that are difficult to classify.

Gradient boosting uses gradient descent to minimize error at each iteration, allowing the model to find more accurate boundaries between classes.
