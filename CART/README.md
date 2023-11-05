# Python CART

[![Open in Colab](https://img.shields.io/badge/Open%20in%20Colab-Open-blue?logo=google-colab)](https://drive.google.com/file/d/13yLJcmOrtsbkJR_6pImHpuN6KZg3Y03A/view?usp=sharing)

[CART](https://en.wikipedia.org/wiki/Decision_tree_learning) algorithm implementation in Python.

## Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/13yLJcmOrtsbkJR_6pImHpuN6KZg3Y03A/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

## Samples

### Dataset

The training and testing datasets were taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/), using the [Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris).

The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant.  One class is linearly separable from the other 2; the latter are not linearly separable from each other.

### Analysis

Let's classify the training data into different levels of the decision tree:

| Number of levels | Accuracy |
|---|---|
|1|	0.592|
|2|	**0.925**|
|3|	0.9|
|4|	**0.925**|
|5|	**0.925**|
|6|	0.91(6)|
|7|	0.892|
|8|	0.9|
|9|	0.892|

As you can see, the algorithm produces high accuracy already at the second level.

### Conclusion

To use the CART algorithm, there is no need to pre-select the variables that will participate in the analysis, and the algorithm is also quite fast. However, the decision trees proposed by the algorithm are not stable: the result obtained on one sample may not be reproducible on another.
