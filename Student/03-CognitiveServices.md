# Challenge 3 - Working with Cognitive Services

## Prerequisites

1. [Challenge 2 - Working with Data in Power BI](./02-Dataflows.md) should be done successfully.


## Introduction

Adventure Works has been getting great business value out of the new model published in Power BI.  Now that users are gaining new insights into historical data they are asking for some advanced analytics features to get additional value and insights from the existing data. The Adventure Works analytics team quickly realized that they don't have the expertise to write artificial intelligence models.  They would like to leverage some native features of the cloud to apply AI to their existing data.  Presently they have a need to do the following:
*   Adventure Works sells products around the world, so they need to identify the language used in a public review.
*   Some of the customers leave very verbose reviews. While getting positive feedback is always nice, Adventure Works is most concerned about negative feedback and would like to analyze the sentiment of a review quickly to find the negative reviews.
*   Since many of the reviews are very long, it would be great to extract some key details about the review from the larger text.
*   Optional:  Adventure Works would like to classify the images in the products table.

The data warehouse team has the request to add reviews information to the data warehouse on their feature backlog, so you'll have to acquire the file from the team that runs the Adventure Works website.  The team has been kind enough to extract the data for you as a delimited file in blob storage.

## Success Criteria
1.  Extend the data flow to bring in data from the product reviews delimited file
1.  Implement cognitive services on the product reviews data to include language, sentiment, and key phrases
1.  In Power BI build one or more reports that demonstrates:
    *   Review count by language
    *   Which type of bikes have the lowest average sentiment
    * Key phrases for all reviews with a sentiment below .5

## Hints
* While Bike Reviews are stored in a blob, you have a URL with a Secure Access Signature that is sufficient to access the file anonymously (with no further authentication besides the URL). What data source connector in Power BI supports anonymous connections to data hosted on the Internet?
*   Technically these cognitive services can be run in any order, because the language detection is not a required input.  Does providing the language alter the results?


## Learning resources

|                                            |                                                                                                                                                       |
| ------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Description**                            |                                                                       **Links**                                                                       |
| Tutorial - Use Cognitive Services in Power BI | <https://docs.microsoft.com/en-us/power-bi/service-cognitive-services> |

[Next challenge (Building Machine Learning in Power BI) >](./04-PowerBIAutoML.md)
