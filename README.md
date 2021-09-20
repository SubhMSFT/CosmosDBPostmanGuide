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

[Securing connectivity to ADLS](#securing-connectivity-to-ADLS) 

[Pattern 1 - Access via Service Principal](#Pattern-1---Access-via-Service-Principal)



[Conclusion](#Conclusion)

[License/Terms of Use](#License/Terms-of-Use)


## Introduction

Azure Cosmos DB is a globally distributed multi-model database that supports the document, graph, and key-value data models. 

For an in-depth coverage of Azure Cosmos DB, you can visit the following links from Microsoft Official Documentation:
- Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/introduction
- Azure C

The Azure Cosmos DB REST API provides programmatic access to Azure Cosmos DB resources to create, query, and delete databases, document collections, and documents. To perform operations on Azure Cosmos DB resources, you send HTTPS requests with a supported method: GET, POST, PUT, or DELETE to an endpoint that targets a resource collection or a specific resource. This section explains how to work with resources by using the REST API.
