# Microsoft Azure Cosmos DB REST APIs Postman Guide
Step-by-step guidance for testing Azure Cosmos DB resources using REST APIs with [Postman](https://www.postman.com/product/what-is-postman/).

**Summary:**

This document provides guidance on how to setup Postman for testing and working with Azure Cosmos DB resources using REST APIs.

**Versions: **

| **Name** | **Title** | **Notes** | **Date** |
| --- | --- | --- | --- |
| Subhasish Ghosh | Cloud Solution Architect – Data &amp; AI, Microsoft EC-US, Global CSU | Original | 20 September 2021 |
|   |   |   |   |

# Contents

[Introduction](#Introduction)

[Creating an Azure Cosmos DB Account](#creating-cosmos-db-account) 

[Pattern 1 - Access via Service Principal](#Pattern-1---Access-via-Service-Principal)



[Conclusion](#Conclusion)

[License/Terms of Use](#License/Terms-of-Use)


## Introduction

Azure Cosmos DB is a globally distributed multi-model database that supports the document, graph, and key-value data models. 

For an in-depth coverage of Azure Cosmos DB, you can visit the following links from Microsoft Official Documentation:
- An [introduction](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) to Azure Cosmos DB
- [Considerations](https://docs.microsoft.com/en-us/azure/cosmos-db/choose-api#considerations-when-choosing-an-api) when choosing an API in Azure Cosmos DB

Postman is an API platform for building and using APIs. 
- Why use Postman? Simply put, Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs — faster.

The Azure Cosmos DB REST API provides programmatic access to Azure Cosmos DB resources to create, query, and delete databases, document collections, and documents. To perform operations on Azure Cosmos DB resources, you send HTTPS requests with a supported method: GET, POST, PUT, or DELETE to an endpoint that targets a resource collection or a specific resource.

## Creating an Azure Cosmos DB Account

Follow this [quickstart](https://docs.microsoft.com/en-us/azure/cosmos-db/sql/create-cosmosdb-resources-portal) to use the Azure portal to create an Azure Cosmos DB SQL API account. Once done, please note down the following key items which we will need in Postman:

Go to Keys > "Read-write Keys" and note:
- URI
- PRIMARY KEY

E.g from my account, I have noted down the 2 following items:
![Image1](Essentials.png)



