# Challenge 2 - Working with Data in Power BI

## Prerequisites

1. [Challenge 1 - Setup](./01-Setup.md) should be done successfully.


## Introduction

Adventure Works has been using a variety of reporting tools over the years, but is disillusioned with all of them.  Their CIO recently read a Gartner report on Power BI and is convinced they need to start doing all new report development on Power BI.  In order to prepare for the new report development, you've been tasked to setup a dataflow for some data in the warehouse. You will then use the entities in your dataflow to build Power BI models.  Presently they have a need to represent the following data in the model:
*   Products
*   Customers
*   Sales
*   Fiscal Calendar

It is important to note that the Adventure Works IT team had originally built their data warehouse on a ["snowflake" schema](https://learning.oreilly.com/library/view/data-warehousing-fundamentals/9780471412540/9780471412540_the_snowflake_schema.html).  While this design works for the enterprise, the structure of the model separating the product catalog into three tables and customer information into two tables is a source of confusion for business users.  The new model in Power BI should simplify this structure and represent Customer as a single entity and Product as a single entity.


## Success criteria
1.  A data flow built on AdventureWorksDW that includes the business entities in the requirements
1.  A configured refresh schedule for the data flow
1.  A Power BI model which includes all business entities
1.  A report that helps illustrate sales by product and sales by geography that can be filtered / sliced by year

## Hints

1. Your data warehouse database has been pre-provisioned for you. If needed, reach out to your coach for connection strings and credentials.
1. Is there anything interesting or concerning about the data types assigned to some fields?  Should you do anything about that?
1. If you're having issues seeing the dataflow contents you may need to clear your Power BI Dataflow Credentials from Power BI Desktop's credential cache.


## Learning resources

|                                            |                                                                                                                                                       |
| ------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Description**                            |                                                                       **Links**                                                                       |
| Self-service data prep with dataflows | <https://docs.microsoft.com/en-us/power-bi/service-dataflows-overview> |
| Create and use dataflows | <https://docs.microsoft.com/en-us/power-bi/service-dataflows-create-use>  |
| Design a data model in Power BI | <https://docs.microsoft.com/en-us/learn/modules/design-model-power-bi/> |

[Next challenge (Working with Cognitive Services) >](./03-CognitiveServices.md)
