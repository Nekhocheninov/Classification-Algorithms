# Python LogisticRegression

[Logistic regression](https://en.wikipedia.org/wiki/Logistic_regression) algorithm implementation in Python.

### Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/1HeCtOMz_hvpXWRyZ5cn5KFYsVssRVXmg/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

# Samples

[***Dataset***](https://github.com/sdukshis/ml-intro/blob/master/datasets/Davis.csv)

Dependent variables: ['sex']

Independent variables: ['weight', 'height']

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/LogisticRegression/img/img_1.png" width="500">

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/LogisticRegression/img/img_2.png" width="500">

Coefficients: 
 [-58.03319918] [[0.16591461 0.27557928]]

Coefficient of precision: 0.90

Coefficient of recall: 0.88

---

Dependent variables: ['sex']

Independent variables: ['weight', 'height', 'weight^2', 'weight*height', 'height^2']

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/LogisticRegression/img/img_3.png" width="500">

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/LogisticRegression/img/img_4.png" width="500">

Coefficients: 
 [-0.00349398] [[-0.11224792 -0.29908018 -0.0011234   0.00250718  0.00120429]]

Coefficient of precision: 0.90

Coefficient of recall: 0.88
