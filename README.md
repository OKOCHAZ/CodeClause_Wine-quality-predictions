# Introduction

This is a project built to utilize machine learning models to predict wine quality based on wine quality data provided from kaggle.
This project contains temporary Jupyter Notebooks
as this projects could use further improvments in the future.


## Files:

* EDA
* Classfication


These file (Notebooks) uses machine learning models and algorthims to predict the class of the wine in this case the feature or column we would like to predict is quality.


## EDA

Explotory Data Analysis this is a major step for any machine learning project and this step will reveal insights and trend in the data, So first of all in this Notebook we download the data from Kaggle, and then we could explore our data.

The does not containt categorical columns all the data are numeric values, so there is no Hot Encoding to be done in this project.


## Classfication

In this Notebook we start trainning the models so we start by `Random Forrest Classfier` it is a good model for classfication.
Check this link for further info [Random Forrest Classfication](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#:~:text=A%20random%20forest%20classifier.,accuracy%20and%20control%20over%2Dfitting.)


Then we try another model `KNN` k nearest neighbor
This is a simple model for classfication and it uses simple algorthims, You Coulde read more about [KNN](https://www.ibm.com/eg-en/topics/knn#:~:text=What%20is%20the%20k%2Dnearest%20neighbors%20algorithm%3F,-Learn%20about%20the&text=The%20k%2Dnearest%20neighbors%20algorithm%2C%20also%20known%20as%20KNN%20or,of%20an%20individual%20data%20point.)

The Last model is `Logistic Regression`, we try to boos the models accuracy a little in the one.


## Improvments:

This project could use more Feature Engineering to improve the models accuracy.

KNN model is not a great choice for this data set so in the next improvment we could remove or replace it.