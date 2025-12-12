## AWS Database Capacity Planning 
- Its important to plan how database will be used in the cloud
- Thinking about amount of data? 
- How long do you need to keep the data for? 
- Do you need backups that get rotated? 
- How frequently is data being ingested? What type of data, structured like emails, numbers, names etc or unstructured data?
- Planning for failure is important as things will fail
- Do we have server failover in an active-active environment? 
- Do you have incident policy to minimise RTO (Recovery Time Objective)
- Do you have multiple database replicas? Read only, read-write?
- How frequently do you back up the data?
- Where is the back up for the data stored?


### AWS Database Types
- There are generally 2 types of data.
- SQL = Structured Query Language
- Structure and Unstructured databases
- NoSQL database in AWS is something like DocumentDB or DynamoDB
- SQL-compliant databases is something like RDS
-A no structured database has NO schema or a loosely structured schema.
- The schema for a database is a blueprint for what will be stored in it

#### Structured Schema 
- These are very rigid and specific in the types of information it holds
- For example, name, email, phone number, date they registered, payment preference etc
- Similar to rows and collumns 

#### Unstructured Schema
- Has no structure or a rigid criteria for the type of data and how it is stored

### RDS Database engine options
- Amazon Aurora
- MySQL
- MongoDB
- PostgreSQL
- Oracle
- Microsoft SQL Server

### AWS Database planning capacity
- Its helpful to monitor database usage patterns and receive notifications using CloudWatch
- Size databases with extra storage, memory and compute power to accomodate unpredictable demand spikes
- Consider the average concurrent number of connected users
- Consider the amount of stored data as well as data in and out via network daily as this will effect the cost
- Use provisioned IOPS (Inputs and Outputs Operatins Per Second) vs magnetic storage to address busy disk I/O usage
- Optimise database queries to reduce required compute power. Reducing cost
- If data can be accessed from Cache or memory it would be alot quicker than even the quickest IOPS disk

### RDS Proxy
- This is an AWS managed service which pools database connections together to increase connection scalibility
- Reduces failover time due to automatic database failover, no waiting for DNS change