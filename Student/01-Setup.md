# Challenge 1 - Setup

## Prerequisites

1. A computer running Windows that meets the [basic requirements for Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/fundamentals/desktop-get-the-desktop).
1. An [Azure subscription](https://azure.microsoft.com/en-us/free/) with sufficient permissions to create and manage resources.
1. Access to [Power BI Premium](https://powerbi.microsoft.com/en-us/power-bi-premium/), either as part of a Premium Capacity or a Power BI Premium License.
    * As a Microsoft employee, you are granted a Premium Per User License which you can use as part of this Hackathon.


## Introduction 

### Access your source data.

Ensure that you are able to access an Azure SQL Database that hosts the data warehouse that will be the primary source of data for today's hackathon.
**Note: connection strings and credentials will be provided by your coach.**

Ensure that you are able to access the Azure storage blob containing product reviews, which will be the secondary source of your data.
**Use the following blob URL with a corresponding Secure Access Signature:**
https://sabi2ai.blob.core.windows.net/bi2ai/bike%20reviews.csv?sp=r&st=2021-01-20T19:43:24Z&se=2022-01-29T03:43:24Z&spr=https&sv=2019-12-12&sr=b&sig=DdfNr3nNeVs%2BRg3drf3ZYZeheFUTiYk8ZmyDg1AyDz0%3D

### Create a Power BI Workspace hosted on a Premium or Premium Per User Capacity
You will need access to Power BI Premium. Please ensure that you either have access to a Premium Capacity or have a Power BI Premium Per User license.

Create a Workspace in your Power BI environment and assign the workspace to a Premium or a Premium Per User Capacity.

### Validate access to your Azure Subscription
You will need to have access to an Azure Subscription with sufficient permissions to provision new resources. 

Log into the Azure Portal and ensure that you have the necessary permissions. 

**A minimum of one subscription per squad is required.** If your squad does not have access to an Azure Subscription, notify your coach.

## Success Criteria
1. Access to an Azure SQL Server with the the AdventureWorksDW database.
1. Access to the blob containing product review data.
1. Access to an Azure Subscription.
1. Access to Power BI Premium.


## Hints
1. Use appropriate tools to check connectivity to an Azure SQL Database
1. For simplicity, consider using your web browser to check if you have access to a blob
1. Research the minimum level of permissions that you would need to create Azure resources that you will need in this hackathon
1. Research how to check your Power BI license and how to determine whether you have access to a Premium Capacity

## Learning resources

|                                            |                                                                                                                                                       |
| ------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Description**                            |                                                                       **Links**                                                                       |
| Create a new workspace in Power BI | <https://docs.microsoft.com/en-us/power-bi/service-create-the-new-workspaces> |
| Configure and manage capacities | <https://docs.microsoft.com/en-us/power-bi/service-admin-premium-manage> |
| Assign a workspace to a capacity | <https://docs.microsoft.com/en-us/power-bi/admin/service-admin-premium-manage> |

[Next challenge (Working with Data in Power BI) >](./02-Dataflows.md)
