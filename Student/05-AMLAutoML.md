# Challenge 5 - Building Models in Azure Machine Learning AutoML

## Prerequisites

1. [Challenge 4 - Building Machine Learning in Power BI](./04-PowerBIAutoML.md) should be done successfully.

## Introduction
Adventure Works marketing team loves the insights they've been getting from the Bike Buyer predictive model.  They love it so much, they'd like to apply it more broadly and use it from other systems. In addition, the Adenture Works team is eager to learn whether they could exercise a little more control over the model training and feature engineering process, without having extensive machine learning expertise.  Since the current model can only be used by Power BI and since Power BI offers few controsl over model training and feature engineering, you've been asked to help Adventure Works craft an AutoML run in Azure Machine Learning Service, deploy the best model to and endpoint, and finally use that endpoint back in Power BI.

## Success Criteria
1.  A published BikeBuyer model endpoint hosted in Azure ML using AutoML.
1.  Demonstrate usage of the API.
1.  Create a new dataflow in Power BI to leverage the published API.


## Hints
1. To conserve time on this challenge be sure to limit training time to 15 minutes (or less).
1. Machine learning models published in the Azure Machine Learning Service will become visible in the Power BI service for users with appropriate access to the Machine Learnign Workspace.
1.  Have a closer look at the columns in BikeBuyerTraining and Prospective Buyer.  What is different about these two tables?  Are there any differences that could be preventing you from using your model?


## Learning resources

|                                            |                                                                                                                                                       |
| ------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Description**                            |                                                                       **Links**                                                                       |
| Create, explore, and deploy automated machine learning experiments with Azure Machine Learning studio                    |        <https://docs.microsoft.com/en-us/azure/machine-learning/how-to-create-portal-experiments>         |
| Azure Machine Learning integration in Power BI | <https://docs.microsoft.com/en-us/power-bi/service-machine-learning-integration> |


[Optional challenge (Building Machine Learning Models in Azure Machine Learning Designer) >](./06-AMLDesigner.md)