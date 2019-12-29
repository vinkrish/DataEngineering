## Data Warehouse

It is a system (including processes, technologies & data representations) that enables us to support analytical processes.

- It represents an abstracted picture of the business organized by subject area.
- It is highly transformed and structured.
- Data is not loaded to the data warehouse until the use for it has been defined.
- It generally follows an established methodology.

When a data warehouse is developed, a significant amount of effort occurs during the initial stages to analyze data sources and understand business processes. Decisions are made regarding what data to include and exclude from the warehouse.

### A Business Perspective

You are in charge of a retailer’s data infrastructure. Let’s look at some business activities.

- Customers should be able to find goods & make orders
- Inventory Staff should be able to stock, retrieve, and re-order goods
- Delivery Staff should be able to pick up & deliver goods
- HR should be able to assess the performance of sales staff
- Marketing should be able to see the effect of different sales channels
- Management should be able to monitor sales growth

Ask yourself:

- Can I build a database to support these activities?
- Are all of the above questions of the same nature?

Let's take a closer look at details that may affect your data infrastructure.

- Retailer has a nation-wide presence → **Scale?**
- Acquired smaller retailers, brick & mortar shops, online store → **Single database? Complexity?**
- Has support call center & social media accounts → **Tabular data?**
- Customers, Inventory Staff and Delivery staff expect the system to be fast & stable → **Performance**
- HR, Marketing & Sales Reports want a lot information but have not decided yet on everything they need → **Clear Requirements?**

### A Technical Perspective

A data warehouse is a copy of transaction data specifically structured for query and analysis.

A data warehouse is a subject-oriented, integrated, nonvolatile and time-variant collection of data in support of management's decisions.

A data warehouse is a system that retrieves and consolidates data periodically from source systems into a dimensional or normalized data store. It usually keeps years of history and is queried for business intelligence or other analytical activities. It is typically updated in batches, not every time a transaction happens in the source system.

### Data Warehouse Goals

- Simple to understand
- Performant
- Quality Assured
- Handles new questions well
- Secure

A data warehouse only includes data that is processed (structured) and only the data that is necessary to use for reporting or to answer specific business questions.

### Facts & Dimenstions

If you are unsure if a column is a fact or dimension, the simplest rule is that a fact is usually: **Numeric & Additive**

Fact tables:

- Record business events, like an order, a phone call, a book review
- Fact tables columns record events recorded in quantifiable **metrics** like quantity of an item, duration of a call, a book rating.

Dimension tables:

- Record the context of the business events, e.g: who, what, where, why etc.
- Dimension tables columns contain **attributes** like the store at which an item is purchased, or the customer who make the call, etc.
