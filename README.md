# Description of the Project

The "Breast Cancer Dataset" is used in this project. It has df.shape=(569, 31) which means 569 rows and 32 columns.  

    + The link of the datset used  in this project is  -https://www.kaggle.com/uciml/breast-cancer-wisconsin-data 
    + I am importing the important python packages- skelarn, pandas, numpy, seaborn and matplotlib to complete the project.
    + The machine learning models such as  Logistic Regression, Decision Tree, Random Forest, XGBoost, AdaBoost and Gradient Boosting classifier have been used. 
    + The performance of the  machine learnig models have been tested on the basis of accuracy score, confusion matrix, classification report, f1 score and roc auc score.
     
I had tuned hyperparameters  to improve the perforamnce for XGBoost model. The good visualization is also important along with accuracy score in model building. The performance of the model have been  visualized in this project. 

# Problem statement

The full form of XGBoost is eXtreme Gradient Boosting, also called winner for several kaggle competetion machine learning model. Most of the literatues of Machine Learning found in google has described this model as having best accuracy, efficient and feasibility.
            
        It is a decision-tree-based ensemble ML algorithm based on gradient boosting framework. It is considered that XGBoost provides a convenient way of cross-validation.             Cross-validation technique is applied to test the model's overfitting during the training phase. If the model gives good accuracy in training dataset but the model               works very poor in testing unseen dataset then it is called overfitting or a model of low bias and high variance. I have to calculate the model training and testing             errors with different learning rates.As we know that the best technique to choose the learning rate value is between 0 and 1. I will be going to start the test by               putting the learning rate as 0.01. It would easy to see the results through good visualization. I am also going to visualize the training and testing errors and                 accuracies by making a graph. Finally, I will tune the hyperparameters which helps us predict the testing datasets i.e. x_test. 

# Purpose of the project

The purpose of this project is to provide a quick overview of different classifiers used in machine learning.
I compare different classifiers accuracies with XGBoost Classifier and predict why it is important in machine learning model building.
This project is focused in Boosting classifier. It will not cover the bagging part (Here, my goal is to identify some of the classifiers accuracies and compare their accuracies with the XGBoost classfier.

# Reference Documents

I would like to highly recommend to read the article link-https://medium.com/@saugata.paul1010/ensemble-learning-bagging-boosting-stacking-and-cascading-classifiers-in-machine-learning-9c66cb271674. 

    The writer has explained very clearly about the ensemble method. The best part of this article is that he has described about the concept of cascading.
    As per Paul(2018), Cascading is one of the most powerful ensemble learning algorithm which is used by Machine Learning engineers and scientists when they want to be             absolutely dead sure about the accuracy of a result.
        
I had read different articles to prepare this project which are down at end of the project as a reference.
