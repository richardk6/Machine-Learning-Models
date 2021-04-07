# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, I created machine learning models capable of classifying candidate exoplanets from the raw dataset.

I did the following:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

### Preprocess the Data

* Preprocessed the dataset prior to fitting the model.
* Performed feature selection and remove unnecessary features.
* Use  `MinMaxScaler` to scale the numerical data.
* Separated the data into training and testing data.

### Tune Model Parameters

* Used `GridSearch` to tune model parameters.
* Tuned and compared at least two different classifiers.

### Reporting

* In the SVM model, the testing data's accuracy was 79.46%. In the Deep_Learning model, the testing data's accuracy was 84.49%. I tuned both of my models, hoping I could get closer to 85% or higher but did not get higher than the deep learning model. I still believe my deep learning model is good enough to predict new expoplants, if it is only wrong aroud 16% of the time. If I continued to train my model with an even larger data set or adjust how my training and testing data split - I think the accuracy would continue to rise.


- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

##### © 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
