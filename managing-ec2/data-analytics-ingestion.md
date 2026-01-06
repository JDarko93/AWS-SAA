## Amazon Data Ingestion and Analytics Services

### Amazon Athena
- Big data ANSI (American National Standard Institude) SQL querying service for data stored in S3
- Managed service
- Data can be structured, semi-structured or structureless
- Queries executed in parallel across nodes for the utmosts speed in query results

### Amazon QuickSight
- A business intelligence (BI) solution that results in data visualisation and dashboards
- Useful for forcasting tends and conducting what if scenarios
- Supports natural language queries against data in many different sources

### Amazon Kinesis
- Designed for real time ingestion of steaming data
- Managed service and supports auto scaling

### Amazon Glue
- ETL solution 
- Extract is getting the data from the original source into an environment so it can be analysed
- Transform the data so it is in some kind of acceptable insights
- Loading that tranformed data into a target service or database for further processing or storage
- Glue consists of a crawler which is used to scan defined datasources specified
- Can integrate with Amazon Athena 

### AWS Lake Formation Service 
- Data lakes are central, large scaled data repo that is usually secured with encryption of data at rest. Stores data in its original form before Extract or Transform steps
- Define data sources and security policies
- Seamless integration with other AWS analysis services such as Amazon Athena
- Requires specialised knowledge by like a data analysis engineer