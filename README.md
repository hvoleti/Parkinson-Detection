# Parkinson-Detection

## Abstract 

Parkinson’s disease is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness. It has 5 stages to it and 
affects more than 1 million individuals every year in India. This is chronic and has no cure yet. It is a neurodegenerative disorder affecting dopamine-producing 
neurons in the brain.

In this Python machine learning project, using the Python libraries Scikit-learn, Numpy, Pandas, and XGBoost, we will build a model using an XGBClassifier. We’ll 
load the data, get the features and labels, scale the features, then split the dataset, build an XGBClassifier, and then calculate the accuracy of our model.


## Observation

As we run different algorithms on the data, we observe KNN and Random Forest to have the highest accuracy of 97.43% apart from the XG Boost. 

![Screenshot (617)](https://user-images.githubusercontent.com/81815144/195980677-cb95e5bb-29c3-461c-80c0-5c6cedba61ef.png)


So in order to understand which algorithms works better , we use other evaluation methods - F1 score and ROC curves. As a result, we observed the KNN to have AUC score of nearly 1 whereas Random Frest has 0.99.
![Screenshot (619)](https://user-images.githubusercontent.com/81815144/195980838-23f10af9-0190-4425-ae62-80e544203637.png)




Thus, we conclude the model best fits for K-Nearest Neighbors

![Screenshot (618)](https://user-images.githubusercontent.com/81815144/195980795-78ed1c2b-2461-4787-b707-26ae74a32df6.png)


