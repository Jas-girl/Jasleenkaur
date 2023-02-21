* A Data Warehouse (DW) is a relational database that is designed for query and analysis rather than transaction processing
* It includes historical data derived from transaction data from single and multiple sources.
* A Data Warehouse provides integrated, enterprise-wide, historical data and focuses on providing support for decision-makers for data modeling and analysis.
* A Data Warehouse is a group of data specific to the entire organization, not only to a particular group of users.
* It is not used for daily operations and transaction processing but used for making decisions.
* A Data Warehouse can be viewed as a data system with the following attributes:
* It is a database designed for investigative tasks, using data from various applications.
* It supports a relatively small number of clients with relatively long interactions.
* It includes current and historical data to provide a historical perspective of information.
* Its usage is read-intensive.
* It contains a few large tables.
* "Data Warehouse is a subject-oriented, integrated, and time-variant store of information in support of management's decisions."
* A data warehouse target on the modeling and analysis of data for decision-makers.
* Therefore, data warehouses typically provide a concise and straightforward view around a particular subject, such as customer, product, or sales, instead of the global organization's ongoing operations. 
* This is done by excluding data that are not useful concerning the subject and including all data needed by the users to understand the subject.
* A data warehouse integrates various heterogeneous data sources like RDBMS, flat files, and online transaction records.
* It requires performing data cleaning and integration during data warehousing to ensure consistency in naming conventions, attributes types, etc., among different data sources.
* Historical information is kept in a data warehouse. For example, one can retrieve files from 3 months, 6 months, 12 months, or even previous data from a data warehouse. 
* These variations with a transactions system, where often only the most current file is kept.
* The data warehouse is a physically separate data storage, which is transformed from the source operational RDBMS. 
* The operational updates of data do not occur in the data warehouse, i.e., update, insert, and delete operations are not performed.
* It usually requires only two procedures in data accessing: Initial loading of data and access to data. Therefore, the DW does not require transaction processing, recovery, and concurrency capabilities, which allows for substantial speedup of data retrieval.
* Non-Volatile defines that once entered into the warehouse, and data should not change.
* The idea of data warehousing came to the late 1980's when IBM researchers Barry Devlin and Paul Murphy established the "Business Data Warehouse."
* In essence, the data warehousing idea was planned to support an architectural model for the flow of information from the operational system to decisional support environments. The concept attempt to address the various problems associated with the flow, mainly the high costs associated with it.
* In the absence of data warehousing architecture, a vast amount of space was required to support multiple decision support environments. 
* In large corporations, it was ordinary for various decision support environments to operate independently.
* Goals of Data Warehousing
* To help reporting as well as analysis
* Maintain the organization's historical information
* Be the foundation for decision making.
* Need for Data Warehouse
* Data Warehouse is needed for the following reasons:
* Business User: Business users require a data warehouse to view summarized data from the past.
*  Since these people are non-technical, the data may be presented to them in an elementary form.
* Store historical data: Data Warehouse is required to store the time variable data from the past.
*  This input is made to be used for various purposes.
* Make strategic decisions: Some strategies may be depending upon the data in the data warehouse.
*  So, data warehouse contributes to making strategic decisions.
* For data consistency and quality: Bringing the data from different sources at a commonplace, the user can effectively undertake to bring the uniformity and consistency in data.
* High response time: Data warehouse has to be ready for somewhat unexpected loads and types of queries, which demands a significant degree of flexibility and quick response time.
* Benefits of Data Warehouse
* Understand business trends and make better forecasting decisions.
* Data Warehouses are designed to perform well enormous amounts of data.
* The structure of data warehouses is more accessible for end-users to navigate, understand, and query.
* Queries that would be complex in many normalized databases could be easier to build and maintain in data warehouses.
* Data warehousing is an efficient method to manage demand for lots of information from lots of users.
* Data warehousing provide the capabilities to analyze a large amount of historical data.
Prerequisites
* Before learning about Data Warehouse, you must have the fundamental knowledge of basic database concepts such as schema, ER model, structured query language, etc.
# Data Mining
* The data mining tutorial provides basic and advanced concepts of data mining.
* Our data mining tutorial is designed for learners and experts.
* Data mining is one of the most useful techniques that help entrepreneurs, researchers, and individuals to extract valuable information from huge sets of data.
*  Data mining is also called Knowledge Discovery in Database (KDD).
*   The knowledge discovery process includes Data cleaning, Data integration, Data selection, Data transformation, Data mining, Pattern evaluation, and Knowledge presentation.
*   The process of extracting information to identify patterns, trends, and useful data that would allow the business to take the data-driven decision from huge sets of data is called Data Mining.
* In other words, we can say that Data Mining is the process of investigating hidden patterns of information to various perspectives for categorization into useful data, which is collected and assembled in particular areas such as data warehouses, efficient analysis, data mining algorithm, helping decision making and other data requirement to eventually cost-cutting and generating revenue.
* Data mining is the act of automatically searching for large stores of information to find trends and patterns that go beyond simple analysis procedures.
*  Data mining utilizes complex mathematical algorithms for data segments and evaluates the probability of future events.
* Data Mining is also called Knowledge Discovery of Data (KDD).
* Data Mining is a process used by organizations to extract specific data from huge databases to solve business problems. 
* It primarily turns raw data into useful information.
* Data Mining is similar to Data Science carried out by a person, in a specific situation, on a particular data set, with an objective.
*  This process includes various types of services such as text mining, web mining, audio and video mining, pictorial data mining, and social media mining.
*  It is done through software that is simple or highly specific. By outsourcing data mining, all the work can be done faster with low operation costs.
*  Specialized firms can also use new technologies to collect data that is impossible to locate manually.
*  There are tonnes of information available on various platforms, but very little knowledge is accessible. 
*  The biggest challenge is to analyze the data to extract important information that can be used to solve a problem or for company development. 
* There are many powerful instruments and techniques available to mine data and find better insight from it.
* Our Data mining tutorial includes all topics of Data mining such as applications, Data mining vs Machine learning, Data mining tools, Social Media Data mining, Data mining techniques, Clustering in data mining, Challenges in Data mining, etc.
* Types of Data Mining
* Data mining can be performed on the following types of data:
* Relational Database:
* A relational database is a collection of multiple data sets formally organized by tables, records, and columns from which data can be accessed in various ways without having to recognize the database tables. 
* Tables convey and share information, which facilitates data searchability, reporting, and organization.
* Data warehouses:
* A Data Warehouse is the technology that collects the data from various sources within the organization to provide meaningful business insights.
*  The huge amount of data comes from multiple places such as Marketing and Finance. 
*  The extracted data is utilized for analytical purposes and helps in decision- making for a business organization. 
*  The data warehouse is designed for the analysis of data rather than transaction processing.
* Data Repositories:
* The Data Repository generally refers to a destination for data storage. 
* However, many IT professionals utilize the term more clearly to refer to a specific kind of setup within an IT structure. 
* For example, a group of databases, where an organization has kept various kinds of information.
* Object-Relational Database:
* A combination of an object-oriented database model and relational database model is called an object-relational model. 
* It supports Classes, Objects, Inheritance, etc.
* One of the primary objectives of the Object-relational data model is to close the gap between the Relational database and the object-oriented model practices frequently utilized in many programming languages, for example, C++, Java, C#, and so on.
* Transactional Database:
* A transactional database refers to a database management system (DBMS) that has the potential to undo a database transaction if it is not performed appropriately.
* Even though this was a unique capability a very long while back, today, most of the relational database systems support transactional database activities.
* The Data Mining technique enables organizations to obtain knowledge-based data.
* Data mining enables organizations to make lucrative modifications in operation and production.
* Compared with other statistical data applications, data mining is a cost-efficient.
* Data Mining helps the decision-making process of an organization.
* It Facilitates the automated discovery of hidden patterns as well as the prediction of trends and behaviors.
* It can be induced in the new system as well as the existing platforms.
* It is a quick process that makes it easy for new users to analyze enormous amounts of data in a short time.
* There is a probability that the organizations may sell useful data of customers to other organizations for money. As per the report, American Express has sold credit card purchases of their customers to other organizations.
