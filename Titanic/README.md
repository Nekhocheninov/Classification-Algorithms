# Python Titanic

[![Open in Colab](https://img.shields.io/badge/Open%20in%20Colab-Open-blue?logo=google-colab)](https://drive.google.com/file/d/11ZWbg346w_XPmWBzy9S71BhhQMPlt85U/view?usp=sharing)

Logistic regression model for competition [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview) in Python.

## Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/11ZWbg346w_XPmWBzy9S71BhhQMPlt85U/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

## Samples

Dependent variables: ['Survived']

Independent variables: ['Pclass', 'Sex', 'Age', 'SibSp', 'Parch', 'Cabin', 'Embarked']

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/Titanic/img/img_1.png" width="500">

Coefficients: 
 [7.62645066] [[-1.08099579 -2.48489482 -0.04232364 -0.33432514 -0.03708441  0.12367239
  -0.20175293]]
  
Coefficient of precision: 0.7910

Coefficient of recall: 0.7361

---

Dependent variables: ['Survived']

Independent variables: ['Pclass', 'Sex', 'Age', 'SibSp', 'Parch', 'Cabin', 'Embarked', 'Title']

<img src="https://github.com/Nekhocheninov/ClassificationAlgorithms/blob/main/Titanic/img/img_2.png" width="500">

Coefficients: 
 [6.57421993] [[-1.01383027 -2.19624466 -0.03653524 -0.38132683 -0.0513771   0.13707966
  -0.20054561  0.31303611]]
  
Coefficient of precision: 0.7904

Coefficient of recall: 0.7465
