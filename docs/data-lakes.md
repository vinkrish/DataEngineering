# Data Lake

A Data Lake is a pool of unstructured and structured data, stored as-is, without a specific purpose in mind, that can be “built on multiple technologies such as Hadoop, NoSQL, Amazon Simple Storage Service, a relational database, or various combinations thereof”. Data is transformed and schema is applied to fulfill the needs of analysis.

A Data Lake allows multiple points of collection and multiple points of access for large volumes of data. A Data Lake is characterized by three key attributes:

1. **Collect everything**: A Data Lake contains all data, both raw sources over extended periods of time as well as any processed data.
2. **Dive in anywhere**: A Data Lake enables users across multiple business units to refine, explore and enrich data on their terms.
3. **Flexible access**: A Data Lake enables multiple data access patterns across a shared infrastructure: batch, interactive, online,search, in-memory and other processing engines.

## Analyze Data Forward and Backward in Time

The Data Lake allows collection of data for future needs before it’s possible to know what those needs are, so it has tremendous potential. Data is not limited by the scope of thinking present when the data is captured, but is free to answer questions we don’t yet know to ask: “Data itself is no longer restrained by initial schema decisions, and can be exploited more freely by the enterprise”.

## Data Lakes Born out of Social Media Giants

The basic concepts behind Hadoop were devised by Google to meet its need for a flexible, cost-effective data processing model that could scale as data volumes grew faster than ever. Yahoo, Facebook, Netflix, and others whose business models also are based on managing enormous data volumes quickly adopted similar methods. Costs were certainly a factor, as Hadoop can be 10 to 100 times less expensive to deploy than conventional data warehousing. Another driver of adoption has been the opportunity to defer labor-intensive schema development and data cleanup until an organization has identified a clear business need. And Data Lakes are more suitable for the less-structured data these companies needed to process.

## Data Lakes compared to Data Warehouses

Depending on the requirements, a typical organization will require both a data warehouse and a data lake as they serve different needs, and use cases.

A data warehouse is a database optimized to analyze relational data coming from transactional systems and line of business applications. The data structure, and schema are defined in advance to optimize for fast SQL queries, where the results are typically used for operational reporting and analysis. Data is cleaned, enriched, and transformed so it can act as the “single source of truth” that users can trust.

A data lake is different, because it stores relational data from line of business applications, and non-relational data from mobile apps, IoT devices, and social media. The structure of the data or schema is not defined when data is captured. This means you can store all of your data without careful design or the need to know what questions you might need answers for in the future. Different types of analytics on your data like SQL queries, big data analytics, full text search, real-time analytics, and machine learning can be used to uncover insights.

|Characteristics|Data Warehouse|Data Lake|
|---------------|--------------|---------|
|Data|Relational from transactional systems, operational databases, and line of business applications|Non-relational and relational from IoT devices, web sites, mobile apps, social media, and corporate applications|
|Schema|Designed prior to the DW implementation (schema-on-write)|Written at the time of analysis (schema-on-read)|
|Performance|Fastest query results using higher cost storage|Query results getting faster using low-cost storage|
|Data Quality|Highly curated data that serves as the central version of the truth|Any data that may or may not be curated (ie. raw data)|
|Users|Business analysts|Data scientists, Data developers, and Business analysts (using curated data)|
|Agility|Less agile, fixed configuration - cumbersome and time-consuming to change the structure of a data warehouse due to the number of business processes tied to it|Highly agile, configure and reconfigure as needed - relatively easy to make changes to models and queries|
|Analytics|Batch reporting, BI and visualizations|Machine Learning, Predictive analytics, data discovery and profiling|

## Which Approach Should I Choose

The warehouse can continue to operate as it always has and you can start filling your lake with new data sources. You can also use it for an archive repository for your warehouse data that you roll off and actually keep it available to provide your users with access to more data than they have ever had before. As your warehouse ages, you may consider moving it to the data lake or you may continue to offer a hybrid approach.
