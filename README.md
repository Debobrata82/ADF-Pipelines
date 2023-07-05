# What is Azure Data Factory in Data Engineering ?

Azure Data Factory (ADF) is a cloud-based data integration service provided by Microsoft Azure. It enables you to create, schedule, and orchestrate data-driven workflows, allowing you to efficiently ingest, transform, and move data between various on-premises and cloud-based data sources.
Azure Data Factory provides a visual interface and a code-free environment for designing and managing data integration pipelines. It supports a wide range of data sources, including relational databases, non-relational databases, file systems, big data platforms, cloud storage, and software-as-a-service (SaaS) applications.

Key features and capabilities of Azure Data Factory include:

* Data Orchestration: ADF allows you to define complex data workflows by creating pipelines that consist of activities and dependencies. You can define the order and dependencies between activities, transforming and processing data as it moves through the pipeline.
* Data Movement: ADF provides connectors to various data sources, enabling efficient and scalable data movement between different platforms. It supports batch data transfers, real-time streaming, and incremental data updates.
* Data Transformation: ADF supports data transformation activities such as mapping, filtering, aggregating, and enriching data during the data integration process. It provides data wrangling capabilities to shape and clean data before loading it into the target destination.
* Integration with Azure Services: ADF integrates seamlessly with other Azure services, allowing you to leverage the capabilities of Azure Data Lake Storage, Azure Blob Storage, Azure SQL Database, Azure Synapse Analytics, Azure Machine Learning, and more.
* Monitoring and Management: ADF provides monitoring and logging capabilities to track the execution and performance of data pipelines. It integrates with Azure Monitor and Azure Log Analytics for centralized monitoring and management.
* Hybrid Data Integration: ADF supports hybrid data integration scenarios by providing a self-hosted integration runtime. This runtime can be installed on-premises or in a virtual machine environment, allowing connectivity to on-premises data sources and enabling data movement between on-premises and cloud environments.

Azure Data Factory is designed to handle the complexities of modern data integration and provides a scalable and reliable solution for managing data workflows in the cloud. It enables organizations to efficiently integrate and process data from various sources, empowering data-driven decision making and analytics.


# ADF-Pipelines Assignments
This repository will contain ADF pipelines with different use cases and scenarios

As part of the assignment you will learn the following :
* How to create a Linked service to create connectivity between data sources and target definition.  
* How to create a Dataset to fetch data from the sources and persist the data in the destination using different formats like CSV, JSON etc
* How to create different activities as part of data ingestion pipeline .Example, Copy Activity, Lookup, Foreach, If-Else
* How to create generic datasets using parameterised approach to send source and target data during runtime
* How to create dynamic folders to store data in respective folders so that we can avoid data overwrite.
* How to execute multiples pipelines in chain using Execute pipeline
