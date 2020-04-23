# Kaggle-IBM-Watson-Customer-Marketing
This project uses predictive analytics to analyze the most profitable customers and how they interact. Take targeted actions to increase profitable customer response, retention, and growth

## Context
Using Watson Analytics, we can predict behavior to retain your customers. We can analyze all relevant customer data and develop focused customer retention programs.

### Customer Behavoir Analytics

Consumer behavior is the study of how individual customers or group of customers buy, use, and dispose ideas, goods, and services to satisfy their needs and wants.

So the importance of customer analytics is rising, this is because when you analyze your customers, you define who your target market is, then you can decide how you'll reach them.

Access to customer data became easier for many businesses and also customers now have accese to data  and information on similar products and contents competitors have. This makes it critical to many businesses to be able to understand and predict what their customers are likely to purchase or view.

### Data Analysis and Machine Learning
Here is Data Analysis and Machine Learning operation conducted on a dataset from IBM Watson Analytics
This dataset gives information about customers that have been contacted by a car insurance company to propose them 4 differents offers. It reveals a lot about demographics and buying behavior of this customers.
We use predictive analytics to analyze the most profitable customers and how they interact. Take targeted actions to increase profitable customer response, retention, and growth.

### IBM Customer Conversion Rate on Balanced and Imbalanced dataset
#### In this context, unbalanced data refers to classification problems where we have unequal instances for different classes.
#### A balanced dataset is the one that contains equal or almost equal number of samples from the positive and negative class.
The conversion rate of this marketing campaign is 14,32%.
To compare correctly the different machine learning models it is better to work with balanced population.
So you will find 2 files :
* ML_ConversionRate_ImbalancedData.ipynb
* ML_ConversionRate_Balanced_Data.ipynb
The first one use raw data with imbalanced population. On the second one a downsampling method has been used.


## Metrics

**Accuracy**

Correctly predicted  / Total predicted

TP+TN/TP+FP+FN+TN

This Metrics show us how the model is able to predict well if a customer will convert or not


**Precision**

True Positive / Total Positive

TP/TP+FP

Ability of the model not to label as converted a customer that will not be converted


**Recall**

True Positive / Observation that should be predicted positive

TP/TP+FN

Ability of the model to find all the customers that have the best chance to be converted


**F1 Score**

Takes both False Positives and False Negatives into account

`2*(Recall * Precision) / (Recall + Precision)`


F1 score is usually more useful than accuracy, especially for an uneven class distribution.