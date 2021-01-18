# Challenge 1 - Setup

## Prerequisites

1. Your laptop: Windows (VM or Parallels is fine, sorry MacOS or Linux users, Power BI Desktop only runs on Windows).
1. Your Azure Subscription with sufficient permissions to create and manage resources.
1. Access to Power BI Premium - you will need either access to a Premium Capacity or a Power BI Premium License. Note, as a Microsoft employee, you are granted a Premium Per User License, which you can use as part of this Hackathon.


## Introduction 

### Access your source data.

Ensure that you are able to access an Azure SQL Database that hosts the data warehouse that will become the primary source of data for today's hackathon.
**Note: connection strings and credentials will be provided by your coach.**

Ensure that you are able to access a blob containing product reviews, which will be the secondary source of your data.
**Note: blob URL will be provided by your coach.**

### Create a Power BI Workspace hosted on a Premium or Premium Per User Capacity
You will need access to Power BI Premium. Please ensure that you either have access to a Premium Capacity or have a Power BI Premium Per User license.

**Note, as a Microsoft employee, you are granted a Premium Per User License, which you can use as part of this Hackathon.**

Create a Workspace in your Power BI environment and assign the workspace to a Premium or a Premium Per User Capacity.

### Validate access to your Azure Subscription
You will need to have access to an Azure Subscription with sufficient permissions to provision new resources.

Log into the Azure Portal and ensure that you have the necessary permissions. 

**A minimum of one subscription per squad is required.** If your squad does not have access to an Azure Subscription, notify your coach.

## Success Criteria
1. Access to an Azure SQL Server with the the AdventurWorksDW database.
1. Access to the blob containing product review data.
1. Access to an Azure Subscription.
1. Accesss to Power BI Premium.


## Hints
1. Use appropriate tools to check connectivity to an Azure SQL Database
1. For simplicity, consider using your web browser to check if you have access to a blob.
1. Research the minimum level of permissions that you would need to create Azure resources that you will need in this hackathon.
1. Research how to check your Power BI license and how to determine whether you have access to a Premium Capacity.

## Success criteria

1.  A restored version of the Adventure Works Data Warehouse
1.  A Power BI application workspace with assigned premium capacity(Note:  This is the most expensive resource we use in this event.  It's a good idea to pause the capacity when you're not using it.)

## Learning resources

|                                            |                                                                                                                                                       |
| ------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Description**                            |                                                                       **Links**                                                                       |
| Create the new workspace in Power BI | <https://docs.microsoft.com/en-us/power-bi/service-create-the-new-workspaces> |
| Configure and manage capacities | <https://docs.microsoft.com/en-us/power-bi/service-admin-premium-manage> |

[Next challenge (Working with Data in Power BI) >](./02-Dataflows.md)