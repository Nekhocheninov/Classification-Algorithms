# Python AdaBoost & GradientBoosting

implementation of classification algorithms using neural networks in Python.

### Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/19a7wEwMq43pfRDs0DUfBP1mfc0JgxRGv/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

# Samples

### Dataset

The training and testing datasets were taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/), using the [Wine Dataset](https://archive.ics.uci.edu/dataset/109/wine).

These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

### Analysis

Convolutional, stochastic and multilayer neural networks with the following parameters were selected:

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/NeuralNet/img/img_4.PNG" width="500">
<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/NeuralNet/img/img_5.PNG" width="500">
<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/NeuralNet/img/img_6.PNG" width="500">

These neural network models perform equally well on the classification task with an accuracy of 0.4259.

Convolutional neural network training schedule:

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/NeuralNet/img/img_1.PNG" width="500">

Stochastic neural network training schedule:

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/NeuralNet/img/img_2.PNG" width="500">

Multilayer neural network training schedule:

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/NeuralNet/img/img_3.PNG" width="500">

As can be seen from the figures, the convolutional neural network had constant accuracy for the test and training data, the stochastic neural network during the training process produced more accurate results for the test data set at some epochs, and the multilayer neural network produced the same result for other epochs.
