# Data Warehouse

1. What is a Data Warehouse? 
A data warehouse is a central repository of all the data used by different parts of the organization. It is a repository of integrated information for queries and analysis and can be accessed later. When the data has been moved, it needs to be cleaned, formatted, summarized, and supplemented with data from many other sources. And this resulting data warehouse becomes the most dependable data source for report generation and analysis purposes.

2. What is Data Mining?
Data mining is analyzing data from different perspectives, dimensions, and patterns and summarizing them into meaningful content. Data is often retrieved or queried from the database in its format. On the other hand, it can be defined as the method or process of turning raw data into useful information.

3. What is the difference between Data Warehousing and Data Mining?
A data warehouse is for storing data from different transactional databases through the process of extraction, transformation, and loading. Data is stored periodically, and it stores a vast amount of data. Some use cases for data warehouses are product management and development, marketing, finance, banking, etc. It is used for improving operational efficiency and for MIS report generation and analysis purposes. 

Whereas Data Mining is a process of discovering patterns in large datasets by using machine learning methodology, statistics, and database systems. Data is regularly analyzed here and is analyzed mainly on a sample of data. Some use cases are Market Analysis and management, identifying anomaly transactions, corporate analysis, risk management, etc. It is used for improving the business and making better decisions. 

4. What is Data Transformation? 
Data transformation is the process or method of changing data format, structure, or values.

6. Why do we need a Data Warehouse?
The primary reason for a data warehouse is for an organization to get an advantage over its competitors, which also helps the organization make smart decisions. Smarter decisions can only be taken if the executive responsibilities for making such decisions have data at their disposal.

7. What are the key characteristics of a Data Warehouse? 
Some of the major key characteristics of a data warehouse are listed below: 

The part of data can be denormalized so that it can be simplified and improve the performance of the same. 
A huge volume of historical data is stored and used whenever needed. 
Many queries are involved where a lot of data is retrieved to support the queries.
The data load is controlled. 
Ad hoc queries and planned queries are quite common when it comes to data extraction.
8. What is the difference between Database vs. Data Lake vs. Warehouse vs. Data Mart?
The difference between the 3 is as follows:

Database
A database is typically structured with a defined schema so structured data can fit in a database; items are organized as tables with columns, columns indicate attributes and rows indicate an object or entity. It has to be structured and filled in here within all these rows and columns. Columns represent attributes, and rows refer to an object or entity. The database is transactional and generally not designed to perform data analytics. Some examples are Oracle, MySQL, SQL Server, PostgreSQL, MS SQL Server, MongoDB, Cassandra, etc. It is generally used to store and perform business functional or transactional data. You can also take an oracle SQL course to help you learn more.

Data Warehouse
A data warehouse exists on several databases and is used for business intelligence. The data warehouse gathers the data from all these databases and creates a layer to optimize data for analytics. It mainly stores processed, refined, highly modeled, highly standardized, and cleansed data.

Data Lake
A data lake is a centralized repository for structure and unstructured data storage. It can be used to store raw data without any structure schema, and there is no need to perform any ETL or transformation job. Any type of data can be stored here, like images, text, files, and videos, and even it can store machine learning model artifacts, real-time and analytics output, etc. Data retrieval processing can be done via export, so the schema is defined on reading. It mainly stores raw and unprocessed data. The main focus is to capture and store as much data as possible.

Data Mart
Data Mart lies between the data warehouse and Data Lake. It’s a subset of filtered and structured essential data of a specific domain or area for a specific business need. 

9. What is a Data Model?
A data model is simply a diagram that displays a set of tables and the relationship between them. This helps in understanding the purpose of the table as well as its dependency. A data model applies to any software development involving creating database objects to store and manipulate data, including transactional and data warehouse systems. The data model is being designed through three main stages: conceptual, logical, and physical data model.

A conceptual data model is a set of square shapes connected by a line. The square shape represents an entity, and the line represents a relationship between the entities. This is very high level and highly abstract, and key attributes should be here.

The logical data model expands the conceptual model by adding more detail and identifying its key and non-key attributes. Hence, key attributes or attributes define the uniqueness of that entity, such as in the time entity, it’s the date that’s a key attribute. It also considers the relationship type, whether one-to-one, one to many, or many to many.

The physical data model looks similar to a logical data model; however, there are significant changes. Here entities will be replaced by tables, and attributes will be referred to as columns. So tables and columns are words specific to a database. In contrast, entities and attributes are specific to a logical data model design, so a physical data model always refers to these as tables and columns. It should be database technology compatible.

10. What is Data Modelling?
Data Modelling is a very simple step of simplifying an entity here in the concept of data engineering. It will simplify complex software by simply breaking it up into diagrams and further breaking it into flow charts. Flowcharts are a simple representation of how a complex entity can be broken down into a simple diagram. This will give a visual representation, an easier understanding of the complex problem, and even better readability to a person who might not be proficient in that particular software usage.

Data modeling is generally defined as a framework for data to be used within information systems by supporting specific definitions and formats. It is a process used to define and analyze data requirements needed to support the business processes within the boundary of respective information systems in organizations. Therefore, the creation of data modeling involves experienced data modelers working closely with business stakeholders, as well as potential users of the information system.

11. What are the differences between Structured and Unstructured Data?
Structure data is neat, has a known schema, and could fit in a fixed table. It uses the DBMS storage method, and Scaling schemas are complicated. Some of the following protocols are ODBS, SQL, ADO.NET, etc.

Whereas, Unstructured data has no schema or structure. It is mostly unmanaged, very easy to scale in runtime, and can store any type of data. Some of the followed protocols are XML,CSV, SMSM, SMTP, JASON etc.

12. What is an ODS used for? 
An operational data store is used to store data from operational systems, and this data is typically used for reporting and analysis.

14. What is Metadata, and what is it used for?
The definition of Metadata is data about data. Metadata is the context that gives information a richer identity and forms the foundation for its relationship with other data. It can also be a helpful tool that saves time, keeps organized, and helps make the most of the files. Structural Metadata is information about how an object should be categorized to fit into a larger system with other objects. Structural Metadata establishes relationships with other files to be organized and used in many ways. 

Administrative Metadata is information about the history of an object, who used to own it, and what can be done with it. Things like rights, licenses, and permissions. This information is helpful for people managing and taking care of an object.

One data point gains its full meaning only when it’s put in the right context. And the better-organized Metadata will reduce the searching time significantly.

15. What is the difference between ER Modelling vs. Dimensional Modelling?
ER Modelling	Dimension Modelling
Used for OLTP Application design.Optimized for Select / Insert / Update / Delete	Used for OLAP Application design. Optimized for retrieving data and answering business queries.
Revolves around entities and their relationships to capture the process	Revolves around Dimensions for decision making, Doesn’t capture process
The unit of storage is a table.	Cubes are units of storage.
Contains normalized data.	Contains denormalized data
16. What is the difference between View and Materialized View?
A view is to access the data from its table that does not occupy space, and changes get affected in the corresponding tables. In contrast, in the materialized view, pre-calculated data persists, and it has physical data space occupation in the memory, and changes will not get affected in the corresponding tables. The material view concept came from database links, mainly used earlier to make a copy of remote data sets. Nowadays, it’s widely used for performance tuning.

The view always holds the real-time data, whereas Materialized view contains a snapshot of data that may not be real-time. Some methods are available to refresh the data in the Materialized view.

17. What does Data Purging mean?
The data purging name is quite straightforward. It is the process involving methods that can erase data permanently from the storage. Several techniques and strategies can be used for data purging. The process of data forging often contrasts with data deletion, so they are not the same as deleting data is more temporarily while data purging permanently removes the data. This, in turn, frees up more storage and memory space which can be utilized for other purposes. The purging process allows us to archive data even if it is permanently removed from the primary source, giving us an option to recover that data in case we purge it. The deleting process also permanently removes the data but does not necessarily involve keeping a ba, and Itp generally involves insignificant amounts of data.

18. Please provide a couple of current Data Warehouse solutions widely used in the Industry.
There are a couple of solutions available in the market. Some of the major solutions are:

Snowflakes
Oracle Exadata
Apache Hadoop
SAP BW4HANA
Microfocus Vertica
Teradata
AWS Redshift
GCP Big Query
19. Provide a couple of renowned used ETL tools used in the Industry.
Some of the major ETL tools are 

Informatica
Talend
Pentaho
Abnitio
Oracle Data Integrator
Xplenty
Skyvia
Microsoft – SQL Server Integrated Services (SSIS)
20. What is a Slowly Changing Dimension?
A slowly changing dimension (SCD) is one that appropriately manages changes of dimension members over time. It applies when business entity value changes over time and in an ad-hoc manner. 

21. What are the different types of SCD?
There are six sorts of Slowly Changing Dimensions that are commonly used. They are as follows:

Type 0 – Dimension never changes here, dimension is fixed, and no changes are permissible.

Type 1 – No History Update record directly. There’s no record of historical values, only the current state. A kind 1 SCD always reflects the newest values, and the dimension table is overwritten when changes in source data are detected.

Type 2 – Row Versioning Track changes as version records which will be identified by the current flag & active dates, and other metadata. If the source system doesn’t store versions, the info warehouse load process usually detects changes and appropriately manages them during a dimension table.

Type 3 – Previous Value column Track change to a selected attribute, and add a column to point out the previous value, which is updated as further changes occur.

Type 4 – History Table shows the current value in the dimension table, and all changes are tracked and stored in a separate table.

Hybrid SCD – Hybrid SDC utilizes techniques from SCD Types 1, 2, and three to trace change.

Only types 0, 1, and a couple of are widely used, while the others are applied for specific requirements.

22. What is a Factless Fact Table? 
A factless fact is a fact table without any value, and such a table only contains keys from different dimension tables.

23. What is a Fact Table? 
A fact table contains a business process’s measurements, metrics, or facts. It is located in the middle of a star schema or a snowflake schema, and dimension tables surround it. 

24. What are Non-additive Facts? 
Non-additive facts cannot sum up any of the dimensions in the fact table. If there is any change in the dimension, then the same facts can be useful. 

25. What is a Conformed Fact? 
A conformed fact is a table across multiple data marts and fact tables.

26. What is the Core Dimension? 
The core dimension is a Dimension table, which is dedicated to a single fact table or Data Mart.

27. What is Dimensional Data Modeling?
Dimensional modeling is a set of guidelines to design database table structures for easier and faster data retrieval. It is a widely accepted technique. The benefits of using dimensional modeling are its simplicity and faster query performance. Dimension modeling elaborates logical and physical data models to further detail model data and data-related requirements. Dimensional models map the aspects of every process within the business.

Dimensional Modelling is a core design concept used by many data warehouse designers design data warehouses. During this design model, all the info is stored in two sorts of tables. 

Facts table
Dimension table 
The fact table contains the facts or measurements of the business, and the dimension table contains the context of measurements by which the facts are calculated. Dimension modeling is a method of designing a data warehouse.

28. What are the types of Dimensional Modelling?
Types of Dimensional Modelling are listed below: 

Conceptual Modelling 
Logical Modelling 
Physical Modelling
29. What is the difference between E-R modeling and Dimensional modeling? 
The basic difference is that E-R modeling has a logical and physical model while Dimensional modeling has only a physical model. E-R modeling is required to normalize the OLTP database design, whereas dimensional modeling is required to denormalize the ROLAP/MOLAP design. 

30. What is a Dimension Table? 
A dimension table is a type of table that contains attributes of measurements stored in fact tables. It contains hierarchies, categories, and logic that can be used to traverse nodes.

31. What is a Degenerate Dimension? 
In a data warehouse, a degenerate dimension is a dimension key in the fact table that does not have its dimension table. Degenerate dimensions commonly occur when the fact table’s grain is a single transaction (or transaction line).

32. What is the purpose of Cluster Analysis and Data Warehousing?
One of the purposes of cluster analysis is to achieve scalability, so regardless of the quantity of data system will be able to analyze its ability to deal with different kinds of attributes, so no matter the data type, the attributes present in the data set can deal with its discovery of clusters with attribute shape high dimensionality which have multiple dimensions more than 2d to be precise ability to deal with noise, so any inconsistencies in the data to deal with that and interpretability.

33. What is the difference between Agglomerative and Divisive Hierarchical Clustering?
The agglomerative hierarchical constraining method allows clusters to be read from bottom to top so that the program always reads from the sub-component first and then moves to the parent in an upward direction. In contrast, divisive hierarchical clustering uses a top-to-bottom approach in which the parent is visited first and then the child. The agglomerative hierarchical method consists of objects in which each object creates its clusters. These clusters are grouped to form a larger cluster. It is also the process of continuous merging until all the single clusters are merged into a complete big cluster that will consist of the objects of the chart clusters; however, in divisive clustering, the parent cluster is divided into smaller clusters. It keeps on dividing until each cluster has a singular object to represent.

34. What is ODS?
ODS is a database that integrates data from multiple sources for additional data operations. The full form of ODS is the operational data source, unlike the master data source, where the data is not sent back to the operational systems. It may be passed for further operations and to the data warehouse for reporting. In ODS, data can be scrubbed, resolved for redundancy, and checked for compliance with the corresponding business rules, so whatever data is filtered out to see if there is some data redundancy. It is checked and shows whether the data complies with the organization’s business rules.

This data can be used for integrating disparate data from multiple sources so that business operations analysis and reporting can be carried out. This is where most of the data used in the current operation are housed before it’s transferred to the data warehouse for the longer term and storage and archiving. 

For simple queries on small amounts of data, such as finding the status of a customer order, it is easier to find the details from ODS rather than Data warehousing as it does not make sense to search a particular customer order status on a larger dataset which will be more costly to fetch the single records. But for analyses like sentimental analysis, prediction, and anomaly detection where data warehousing will perform the role to play with its large data volumes.

ODS is similar to short-term memory, where it only stores very recent information. On the contrary, the data warehouse is more like a long-term memory storing relatively permanent information because a data warehouse is created permanently.

35. What is the level of granularity of a Fact Table?
A fact table is usually designed at a low level of granularity. This means we must find the lowest amount of information stored in a fact table. For example, employee performance is a very high level of granularity. In contrast, employee performance daily and employee performance weekly can be considered low levels of granularity because they are much more frequently recorded data. The granularity is the lowest level of information stored in the fact table; the depth of the data level is known as granularity in the date dimension.

The level could be a year, month, quarter, period, week, and day of granularity, so the day is the lowest, and the year is the highest. The process consists of the following two steps determining the dimensions to be included and the location to find the hierarchy of each dimension of that information. The above factors of determination will be resent as per the requirements.

36. What’s the biggest difference between Inmon and Kimball’s philosophies of Knowledge Warehousing?
These are two philosophies that we’ve in data warehousing. Within the Kimball philosophy, data warehousing is viewed as a constituency of knowledge mods, so data mods are focused on delivering business objectives for departments in a corporation. Therefore the data warehouse may be a confirmed dimension of the info mods; hence a unified view of the enterprise is often obtained from the dimension modeling on a departmental area level.

Within the Inmon philosophy, we will create a knowledge warehouse on a topic-by-discipline basis; hence, the information warehouse can start with the in-web store’s information. The subject areas are often added to the info warehouse as their need arises point of sale, or pos data are often added later if management decides it’s required. We first accompany data marts if we check it out algorithmically within the Kimball philosophy. We combine it, and we get our data warehouse, while with Inmon philosophy, we create our data warehouse and then create our data marts.

Both differ within the concept of building the info Warehouse. – Kimball views Data Warehousing as a constituency of knowledge marts. Data marts are focused on delivering business objectives for departments in a corporation, and therefore the Data Warehouse may be a conformed dimension of the info Marts. Hence, a unified view of the enterprise is often obtained from the dimension modeling on a departmental area level. – Inmon explains creating a knowledge Warehouse on a subject-by-subject area basis. Hence, the event of the info Warehouse can start with data from the web store. Other subject areas are often added to the info Warehouse as their needs arise. Point-of-sale (POS) data is often added later if management decides it’s necessary.

37. Explain the ETL cycles’ three-layer architecture.
ETL stands for extraction transformation and loading, so three phases are involved in it – the primary is the staging layer. The info integration layer and the last layer is the access layer. So these are the three layers involved in the three specific phases within the ETL cycle, so the staging layer is used for the info extraction from various source data structures.

Within the data integration layer, data from the staging layer is transformed and transferred to the info base using the mixing layer. The data is arranged in hierarchical groups often mentioned as dimensions facts or aggregates during a data warehousing system; the mixture of facts and dimension tables is called a schema, so basically, within the data integration layer, once the info is loaded and data extracted and transformed within the staging layer and eventually the access layer where the info is accessed and may be loaded for further analytics.

38. What’s an OLAP Cube?
The idea behind OLAP was to pre-compute all calculations needed for reporting. Generally, calculations are done through a scheduled batch job processing at non-business hours when the database server is normally idle. The calculated fields are stored in a special database called an OLAP Cube.

An OLAP Cube doesn’t need to loop through any transactions because all the calculations are pre-calculated, providing instant access.

An OLAP Cube may be a snapshot of knowledge at a selected point in time, perhaps at the top of a selected day, week, month, or year.

You’ll refresh the Cube at any time using the present values within the source tables.

With very large data sets, it could take an appreciable amount of your time for Excel to reconstruct the Cube.

But the method appears instantaneous with the info sets we’ve been using (just a few thousand rows).

39. Explain the chameleon method utilized in Data Warehousing.
Chameleon may be a methodology that may be a hierarchical clustering algorithm that overcomes the restrictions of the prevailing models and methods in data warehousing. This method operates on the sparse graph having nodes representing data items and edges representing the weights of the info items. This representation allows large data sets to be created and operated successfully. The tactic finds the clusters utilized in the info set using the two-phase algorithm. The primary phase consists of graph partitioning that permits the clustering of the info items into a larger number of sub-clusters; the second phase, on the opposite hand, uses an agglomerative hierarchical clustering algorithm to look for the clusters that are genuine and may be combined alongside the sub-clusters that are produced.

40. What’s virtual Data Warehousing?
A virtual data warehouse provides a collective view of the finished data. A virtual data warehouse has no historical data and is often considered a logical data model of the given Metadata. Virtual data warehousing is the de facto data system strategy for supporting analytical decisions. It’s one of the simplest ways of translating data and presenting it within the form decision-makers will employ. It provides a semantic map that allows the top user viewing because the data is virtualized.

41. What is Active Data Warehousing?
An active data warehouse represents a single state of a business. Active data warehousing considers the analytical perspectives of customers and suppliers and helps show the updated data through reports. This is the most common form of data warehousing used for large businesses, specifically those that deal in the e-commerce or commerce industry. A form of repository of captured transactional data is known as active data warehousing.

Using this concept, trends and patterns are found to be used for future decision-making. Based on the analytical results from the data warehouse, it can perform other business decisions active data warehouse as a feature that can integrate the data changes. At the same time, scheduled cycles refresh enterprises utilize an active data warehouse and draw the company’s image in a very statistical manner. So everything is essentially a combination of all the data that is present in various data sources. Combine it all and then perform analytics to get insights for further business decisions.

42. What is a snapshot concerning a Data Warehouse?
Snapshots are pretty common in software, especially in databases, so essentially, it is what the name suggests. Snapshot refers to the complete visualization of data at the time of extraction. It occupies less space and can be used to back up and restore data quickly, so essentially, it snapshots a data warehouse when anyone wants to create a backup. So using the data warehouse catalog, It’s creating a report, and the report will be generated as shown as soon as the session is disconnected from the data warehouse. 

43. What is XMLA?
XMLA is XML for analysis, and it is a SOAP-based XML protocol that can be used and considered as a standard for accessing data in the OLAP method, data mining, or data sources on the internet. The simple object access protocol XMLA uses to discover and execute methods that fetch information from the internet. In contrast, the execution allows the application to execute against the data sources in XMLA. XMLA is a standard methodology for accessing data in analytical systems such as OLAP. It is based on XML soap and HTTP XMLA specifies MDXML as a query language in XMLA 1.1 version. The only construct is the MDXML in an MDX statement enclosed in the tag.

44. What is the Junk Dimension?
A Junk Dimension is a dimension table consisting of attributes that do not belong in the fact table or any other existing dimension tables. The characteristics of these attributes are usually text or various flags, e.g., non-generic comments or very simple yes/no or true/false indicators. These attributes typically remain when all the apparent dimensions within the business process are identified. Thus the designer is faced with the challenge of where to place these attributes that don’t belong within the other dimensions.

In some scenarios, data might not be appropriately stored within the schema. The info or attributes are often stored during a junk dimension; the character of the junk during this particular dimension is typically Boolean or flag values. A single dimension is formed by lumping a small number of dimensions, and this is called a junk dimension adjunct dimension has unrelated attributes. The process of grouping these random flags and text attributes in a dimension by transmitting them to a distinguished sub-dimension is related to the junk dimension, so essentially, any data that need not be stored in the data warehouse because it is unnecessary is stored in the junk dimension.

45. What are the different types of SCDs used in data warehousing?
SCDs stand for slowly changing dimensions, and it is a dimension where data changes do not happen frequently or regularly. There are three types of SCDs the first is SCD1, a record used to replace the original. Even when only one record exists within the database, the present data will be replaced, and the new data will take its place.

SCD2 is the new record file that is added to the dimension table. The record exists in the database with the current and previous data stored in the audit or history. 

SCD3 uses the original data that is modified to the new data. This consists of two records, one that exists in the database and the other that will replace the old database record with this new information.

46. Which one is faster: multidimensional OLAP or relational OLAP?
Multi-dimensional OLAP, also known as MOLAP, is faster than relational OLAP for the following reasons in MOLAP. 

The data is stored in a multi-dimensional queue; the storage is not in the relational database but proprietary formats. MOLAP stores all the possible combinations of data in a multidimensional array.

47. What is Hybrid SCD? 
Hybrid SCDs are combinations of both SCD1 and SCD2. It may happen that in a table, some columns are important and need to track changes for them that are captured by the historical data for them. In some columns, even if the data changes, that does not need to bother. For such tables, hybrid SCDs are implemented wherein some columns are of type 1, and some are of type 2. So basically, a blanket rule is not applied to the entire table rather than customized on which particular columns where a particular rule needs to be applied.

48. Why do we overwrite the execute method and struts as parts of the start framework?
We can develop the action servlets and the action form servlets, and other circuit classes in the action form class. You can develop a validated method that can return action errors object in this method. One can also write the validation code if this method returns null or action errors with the size of zero. The web container will call execute as part of the action class, and it will call the execute method if it returns a size greater than zero. It will rather execute the JSP servlet, or the HTML file as the value for the input attribute is part of the attribute in the struts-config XML file.

49. What is VLDB? 
VLDB stands for a very large database, and it is a database that contains a particularly sizable amount of tuples or rows or occupies a particularly large physical file system storage. VLDB database sizes are normally in Terabytes only.

50. How are the Time Dimensions loaded?
Time dimensions are usually loaded by a program that loops through all possible dates appearing within the data, and it’s a common place for 100 years to be represented during a time dimension with one row per day.

51. What are conformed Dimensions?
Conform dimensions can be used across multiple data marks in combination with multiple fact tables. A conformed dimension is a dimension that has the same meaning and contents; when being referred to from different fact tables, it can refer to multiple tables in multiple data marts within the same organization itself.

52. What are the five main Testing Phases of a project?
ETL test is performed in five stages which are the following the identification of data sources and requirements; first, you will identify which data sources you want for your data warehouse and what are the requirement of the data warehouse, and the analytical requirements that your organization needs the acquisition of data naturally after identifying the data source you will acquire that data implementing business logic and dimensional modeling on that data building and publishing that data and the reports that you will create out of the analytics that you perform.

53. What do you mean by the Slice Action, and how many slice-operated dimensions are used?
A slice operation is the filtration process in a data warehouse. It selects a specific dimension from a given cube and provides a new sub-cube in the slice operation. Only a single dimension is used, so, out of a multi-dimensional data warehouse, if it needs a particular dimension that needs further analytics or processing, it will use the slice operation in that data warehouse.

54. What are the stages of Data Warehousing? 
There are 7 Steps to Data Warehousing:

Step 1: Determine Business Objectives 
Step 2: Collect and Analyze Information 
Step 3: Identify Core Business Processes
Step 4: Construct a Conceptual Data Model 
Step 5: Identify Data Sources and Data Transformations planning
Step 6: Set Tracking Duration 
Step 7: Implement the Plan
55. What is the difference between Data Cleaning and Data Transformation? 
Data cleaning is the process that removes data that doesn’t belong in your dataset. Data transformation is how data from one format or structure converts into another. Transformation processes can also be mentioned as data wrangling or data mugging, transforming, and mapping data from one “raw” data form into another for warehousing and analysis. This text focuses on the processes of cleaning that data.

56. What is Normalization? 
Normalization is a multi-step process that puts data into tabular form, removing duplicated data from the relation tables. 

57. What is the benefit of Normalization? 
Normalization helps in reducing data redundancy, and thus it saves physical database spaces and has minimal write operation cost.

58. What is Denormalization in a Database?
Denormalization is employed to access the info from a higher or lower regular database, and it creates redundancy and stores multiple copies of the same data in different tables.

59. What is the benefit of Denormalization? 
Denormalization adds required redundant terms into the tables to avoid using complex joins and many other complex operations. Denormalization doesn’t mean that normalization won’t be done, but the denormalization process takes place after the normalization process.

60. What is an Extent? 
An Extent is a fixed number of contiguous data blocks as per configuration. It is obtained during a single allocation and used to store a specific type of information. 

61. What is an Index? 
An Index is associated with a database table for quick data search or filter operation retrieval. An index can consist of one or more columns associated with it. Different types of indexes are available in databases, like Unique Key indexes, primary key indexes, Bitmap indexes, and B-Tree indexes. Indexes also hold separate tablespace for storing the preferences of data. Indexes are not recommended where insert, update and delete operations frequently occur rather than a select statement.

62. What is a Source Qualifier? 
A source qualifier represents the rows the Server reads when it executes a session. Source qualifier transformation needs to be connected for the addition of a relational or a flat file source definition to a mapping.

63. What is ETL Pipeline?
ETL Pipeline refers to a group of processes to extract the info from one system, transform it, and cargo it into some database or data warehouse. They are built for data warehousing applications that incorporate enterprise data warehouses and subject-specific data marts. They are also used for data migration solutions. Data warehouse/ business intelligence engineers build ETL pipelines.

64. What is the Data Pipeline?
Data Pipeline refers to any set of process elements that move data from one system to a different one. Data Pipeline is often built for an application that uses data to bring value. It is often used to integrate the info across the applications, build info-driven web products, and complete data mining activities. Data engineers build the data pipeline.

65. What is a Fact? What are the types of Facts?
A fact may be a central component of a multi-dimensional model that contains the measures to be analyzed. Facts are related to dimensions.

Types of facts are:

Additive Facts
Semi-additive Facts
Non-additive Facts
66. What is a dimensional model in a data warehouse?
A dimensional model is a design approach for organizing data in a data warehouse. It consists of fact tables and dimension tables. Fact tables store quantitative data (e.g., sales, cost, revenue) and are typically linked to one or more dimension tables, which store descriptive data (e.g., product, customer, time). Dimensional modeling lets users quickly understand and analyze data by breaking it down into smaller, more manageable pieces.

67. What is ETL in a data warehouse?
ETL stands for Extract, Transform, and Load. It is a process for extracting data from various sources, transforming it into a suitable format for the data warehouse, and loading it into the target system. ETL helps to integrate data from different sources, enforce data quality standards, and prepare data for reporting and analysis.

68. What is a slowly changing dimension in a data warehouse?
A slowly changing dimension is a type of dimension table in a data warehouse that stores data that changes gradually over time (e.g., customer name, address). There are three types of slowly changing dimensions: Type 1 (overwrite), Type 2 (add a new row), and Type 3 (add a new column). Each type has its pros and cons, and the appropriate approach depends on the requirements and constraints of the data warehouse.

69. What is a star schema in a data warehouse?
A star schema is a type of dimensional model in a data warehouse that consists of one or more fact tables and a set of dimension tables. The fact tables and dimension tables are connected through foreign key-primary vital relationships, and the fact tables contain the primary data points used for analysis. The star schema is simple, easy to understand, and performs well for querying and reporting.

70. What is a snowflake schema in a data warehouse?
A snowflake schema is a type of dimensional model in a data warehouse that is more normalized and complex than a star schema. It consists of fact and dimension tables connected through multiple levels of foreign key-primary vital relationships. While the snowflake schema is more adaptable than the star schema, it can also be slower and trickier.

71. What is a factless fact table in a data warehouse?
A factless fact table is a type of fact table in a data warehouse that does not contain any quantitative data (i.e., measures). It records events or transactions with no numeric value (e.g., attendance, registration). Factless fact tables are often used in conjunction with other fact tables to track and analyze events and processes in a data warehouse.

72. What is a Type 2 SCD in a data warehouse?
A Type 2 Slowly Changing Dimension (SCD) is a type of slowly changing dimension in a data warehouse that tracks changes by adding a new row to the dimension table instead of overwriting the existing data. This method is helpful when monitoring and maintaining dimension data changes over time rather than replacing them with the most recent information.

Conclusion
We are at the end of the blog on the top 66 data warehouse interview questions. We hope you found this helpful and are now better equipped to attend your upcoming interview sessions. If you wish to learn more about such concepts, join Great Learning’s PGP Data Science and Business Analytics Course to upskill today. Great Learning also offers mentor support, interview preparation, and live sessions with industry experts! 

The 12-week Applied Data Science Program has a curriculum carefully crafted by MIT faculty to provide the skills, knowledge, and confidence you need to flourish in the Industry. The program not only focuses on Recommendation Systems but also on other business-relevant technologies, such as Machine Learning, Deep Learning, and more. The top-rated data science program prepares you to be an important part of data science efforts at any organization.

Also, Read the Top 25 Common Interview Questions

Frequently Asked Questions
What are the 5 components of a data warehouse?
There are primarily 5 components of Data Warehouse Architecture: 

1) Database 
2) ETL Tools 
3) Meta Data 
4) Query Tools 
5) DataMarts

What are the basic 4 features of data warehousing?
The primary 4 features of data warehousing are as follows:

1) Subject-oriented
2) Time-variant
3) Integrated
44) Persistent & non-volatile

What are the three main types of data warehouses?
The three main types of Data warehouses are Enterprise Data Warehouse (EDW), Operational Data Store, and Data Mart.

What is ETL in data warehousing?
ETL, short for extract, transform, and load, is ideally a  data integration system known to bring together data from several data sources into a reliable data store that is then loaded into a data warehouse or other destination point.

What are OLAP and OLTP?
Although both terms may sound similar, they have some distinct qualities. Online transaction processing (OLTP) is the real-time capture, archiving, and processing of data from transactions. Complex queries are used in online analytical processing (OLAP) to examine past aggregated data from OLTP systems.

Avatar photo
Great Learning
Great Learning's Blog covers the latest developments and innovations in technology that can be leveraged to build rewarding careers. You'll find career guides, tech tutorials and industry news to keep yourself updated with the fast-changing world of tech and business.
Recommended for you

Data Science Applications
data science movies
Top 7 Movies Every Data Scientist Must Watch
lasso regression
A Complete understanding of LASSO Regression
Factorial Python
Python Program to Find the Factorial of a Number

Top 25 Data Science Books in 2023- Learn Data Science Like an Expert
Career Transition From Data Analyst to Data Scientist
Top Data Analytics Jobs in 2023
Leave a Comment
Your email address will not be published. Required fields are marked *


Type here..
Type here..
Name*
Name*

Email*
Email*

Website
Website

 Save my name, email, and website in this browser for the next time I comment.



Crack dream jobs with FREE certificate courses on India's most trusted education platform
EXPLORE FREE ONLINE COURSES
Free Courses
Python for Machine Learning
Data Science Foundations
Deep Learning with Python
Introduction to Cyber Security
Introduction to Digital Marketing
Java Programming
View More →
Blog Categories
Data Science
Artificial Intelligence
Career
Cybersecurity
Full Stack Development
Popular Courses
PGP In Data Science and Business Analytics
PGP In Artificial Intelligence And Machine Learning
PGP In Management
PGP In Cloud Computing
Software Engineering Course
PGP In Digital Marketing
View More →
Salary Blogs
Salary Calculator
Data Architect Salary
Cloud Engineer Salary
Software Engineer Salary
Product Manager Salary
Interview Questions
Java Interview Questions
Python Interview Questions
SQL Interview Questions
Selenium Interview Questions
Machine Learning Interview Questions
NLP Interview Questions
View More →
Quick Links
About Us
Contact Us
Privacy Policy
Terms of Use
Great Learning Careers
    
About Us
Contact Us
Privacy Policy
Terms of Use
Great Learning Careers
© 2013 - 2023 Great Lakes E-Learning Services Pvt. Ltd. All rights reserved

Get our android app
Get our ios app

Free CoursesMenu Toggle
CareerMenu Toggle
Work with UsMenu Toggle
Free CoursesMenu Toggle
CareerMenu Toggle
Work with UsMenu Toggle
 
