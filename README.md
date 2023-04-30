# Microsoft Purview In A Day

Microsoft Purview In A Day is a single day event which is all about Data Governance. During the day you'll participate in different presentations, inspiration sessions and hands-on challenges. It provides a good balance between state-of-the-art theory and hands-on experience.

The Purview In A Day is all about 2 challenges in which you'll be enabled with relevant concepts, and go deep in a hands-on exercises.

![Mission statement](./assets/dgf-mission-statement.png)

## What is Microsoft Purview?

Microsoft Purview is a unified data governance service that helps you manage and govern your on-premises, multi-cloud and software-as-a-service (SaaS) data. Easily create a holistic, up-to-date map of your data landscape with automated data discovery, sensitive data classification and end-to-end data lineage. Empower data consumers to find valuable, trustworthy data.

## :books: Preface

- [Preface: Introduction to Data Governance and Purview](./modules/preface.md)

## Challenge 1

During the first challenge, you'll setup the lab environment in a Azure subscription (see Azure Pass below). We will create the required resources in a `resource group` using a predefined script, and activate the Microsoft Purview service.

Once you're all set, we will create a new collection in Microsoft Purview, and connect to two resources `Microsoft SQL Database` and the `Azure Data Lake`. Once connected, we will start scanning our data sources to extract the technical metadata. We're now able to search, and further document our data model.

## Challenge 2

[Cedric] To be completed with a concrete explanation.

## :thinking: Prerequisites

To complete this workshow you'll need to have access to an Azure subscription, and be able to install a custom template.

- An [Azure account](https://azure.microsoft.com/free/) with an active subscription. Note: If you don't have access to an Azure subscription, you may be able to start with a [free account](https://www.azure.com/free).
- You must have the necessary privileges within your Azure subscription to create resources, perform role assignments, register resource providers (if required), etc.
- If you have no free account, you can leverage your Azure Pass in your Azure account. [Register Azure Pass](https://azure.microsoft.com/en-us/pricing/offers/azure-pass/).

## :books: Challenge 1

Before getting started make sure to setup the [Lab Environment](./modules/module00.md) and [create you Microsoft Purview Account](./modules/module01.md). This is a prerequisite before working on the challenges!

- [Lab Environment](./modules/module00.md)
- [Create a Microsoft Purview Account](./modules/module01.md)

Let's go!

1. [Register & Scan: Azure Data Lake Storage Gen2 ](./modules/module02a.md)
2. [Register & Scan: Azure SQL Database](./modules/module02b.md)
3. [Search & Browse](./modules/module03.md)
4. [Glossary](./modules/module04.md)
5. [Classifications](./modules/module05.md)
6. [Lineage](./modules/module06.md)

## :books: Challenge 2

7. [Insights](./modules/module07.md)
8. [Monitor](./modules/module08.md)
9. [REST API](./modules/module10.md)
10. [Data Sharing](./modules/module16.md)
11. [Metamodel](./modules/module17.md)

<div align="right"><a href="#microsoft-purview-workshop">↥ back to top</a></div>

## All Modules

If you are doing with challenge 1 and challenge 2, feel free to explore all modules from this Purview lab.

1. [Create a Microsoft Purview Account](./modules/module01.md)
2. Register & Scan: [2A. Azure Data Lake Storage Gen2 (Managed Identity)](./modules/module02a.md) | [2B. Azure SQL Database (Azure Key Vault)](./modules/module02b.md)
3. [Search & Browse](./modules/module03.md)
4. [Glossary](./modules/module04.md)
5. [Classifications](./modules/module05.md)
6. [Lineage](./modules/module06.md)
7. [Insights](./modules/module07.md)
8. [Monitor](./modules/module08.md)
9. [Integrate with Azure Synapse Analytics](./modules/module09.md)
10. [REST API](./modules/module10.md)
11. [Securely scan sources using Self-Hosted Integration Runtimes](./modules/module11.md)
12. [Managed private endpoints](./modules/module12.md)
13. [Process events using Atlas Kafka topics via Event Hubs and NodeJS](./modules/module13.md)
14. [Data owner policies (Azure Storage)](./modules/module14.md)
15. [Azure SQL Database Lineage Extraction](./modules/module15.md)
16. [Data Sharing](./modules/module16.md)
17. [Metamodel](./modules/module17.md)
