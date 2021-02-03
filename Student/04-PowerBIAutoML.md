# Challenge 4 - Building Machine Learning Models in Power BI

## Prerequisites

1. [Challenge 3 - Working with Cognitive Services](./03-CognitiveServices.md) should be done successfully.

## Introduction
The Adventure Works business users have loved all the additional insights they've been getting form the text analytics features added to the model.  They'd love to take their advanced analytics to the next level by trying to predict outcomes.  Adventure Works makes most of its income off of selling big ticket items like bikes, in order to try and increase bike sales marketing has acquired a list of prospective customers.   The marketing team would like to assess which of these customers is most likely to buy a bike so they can send a targeted mailing to a select group of customers.

## Success Criteria
1.  Leverage the existing customer data to train a model to predict buying a bike
1.  Score the list of prospective customers for their propensity to buy a bike
1.  In Power BI build one or more reports to highlight which customers are most likely to buy a bike
1.  Generate the model performance report so see metrics about the model created by Auto ML
1.  Explain the impact of increasing or decreasing the probability threshold on the performance of your model, such as precision and recall.


## Hints
1. A view called BikeBuyerTraining was already added to the data warehouse to provide the necessary data for trainig the machine learning model.
1. To conserve time on this challenge be sure to limit training time to 15 minutes (or less).
1.  When scoring the list of prospective buyers, take a closer look at the columns in BikeBuyerTraining and Prospective Buyer.  What is different about these two tables?  Are there any differences that could be preventing you from using your model?

## Learning resources

|                                            |                                                                                                                                                       |
| ------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Description**                            |                                                                       **Links**                                                                       |
| Automated Machine Learning in Power BI | <https://docs.microsoft.com/en-us/power-bi/service-machine-learning-automated> |
| Tutorial: Build a Machine Learning model in Power BI | <https://docs.microsoft.com/en-us/power-bi/service-tutorial-build-machine-learning-model> |
| Age Calculation in Power BI using Power Query | <https://radacad.com/age-calculation-in-power-bi-using-power-query> | 
| Precision and recall | <https://en.wikipedia.org/wiki/Precision_and_recall>|


[Next challenge (Building Models in Azure Machine Learning - AutoML) >](./05-AMLAutoML.md)
