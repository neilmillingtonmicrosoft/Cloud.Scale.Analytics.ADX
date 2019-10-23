Lab 1 -- Automated File Ingestion & Analytics

Lab Summary
-----------

This solution architecture provides support for data ingestion for both
structured and unstructured data curation.

Land files (at scale if required -- 100s per second) to Azure Blob,
triggering automatic file ingestion into Azure Data Lake (Gen-2) via an
Azure Data Factory pipeline. Data can be ingested into ADX or queried
via an external table reference. The lab can easily be enhanced to
include structured/relational datastores (SQL Server, PostgreSQL) or
semi-structured/non-relational datastores (e.g. Cosmos DB).

This **README.MD** file explains how the workshop is structured, what
you will learn, and the technologies you will use in this solution.

There is a small set of sample JSON formatted data however the lab guide
indicates how other data formats can be processed.

Activities
----------

The lab is broken down into several logical units, as follows:

-   Activity 1 -- Azure Blob, Azure Data Lake (ADLS)

    -   Build these Azure services

-   Activity 2 - Key Vault, Event Grid

    -   Build these Azure services

-   Activity 3 - Data Factory

    -   Build these Azure services

-   Activity 4 -- Azure Data Explorer (ADX)

    -   Build these Azure services

-   Activity 5 -- Security & Access

    -   Configure storage SAS keys

-   Activity 6 -- ADF Pipeline

    -   Build an ADF pipeline, triggered by Event Grid

-   Activity 7 -- Execute ADF Pipeline

    -   Run the ADF pipeline with sample data

-   Activity 8 -- ADX integration with ADLS

The first five activities are associated with building the environment
that will be used in this and subsequent labs. Lab activities 6 & 7
build and execute an ADF pipeline associated with automated file
ingestion. Lab activity 8 gives a summary example of dynamic analytics
with data residing in a data lake.

Lab 1 -- Architecture
---------------------

The diagram below shows the architecture that will be built in Lab 1.

![](media/image1.png){width="6.268055555555556in"
height="3.5256944444444445in"}

Method
------

Open the lab document "Azure Cloud Scale Analytics with ADX - Lab 1
Instructions.pdf" and work through each activity to complete the lab.