## Business continuity

- Incident response plans (IRP) are crucial to proactively plan ahead for how specific types of incidents will be dealt with in real time

- Disaster recovery plan (DRP) is vital for giving guides for how to recovery a failed system. Like restore data from backup


### Disaster Recovery (DR)

- Recovery time objective (RTO) is the maximum allowable downtime. Measured in time. For example a customer database server can only be down for 1 hour before it causes more significant issues

- Recovery point objective (RPO) is maximum tolerable amount of data loss measured in time. For example, a company can only afford to lose 1 hour of customer transaction data before significant issues

- This heavily relates to how often you make backups of your transactions to help minimise this becoming and issue


### Proactive failure planning 

- Application load balancer can help with the apps availability and performance by spreading out the workload across multiple instances and not solely relying on one instance

- S3 bucket replication can be configured for different regions. Meaning high availability of data in the bucket as it is replicated across different regions, should something happen within a specific region

- Database replicas also works similar to the s3 bucket replication 



### Application resilience 

- Warm standby, pilot light DR strategy (active-passing) high availability solutions. This is when you hhave a copy of an application that is available on another host, but not able to run at full capacity

- Pilot light is when you have the shell of a secondary solution for failure such as having an auto scaling group configured but no instances running st the same time

- Failover which means failing over to another copy of the app such as being routed to another instance behind the application load balancer

- Failback means after the original server failed comes back online, you can fail the service back to that host. Mostly used in clustering environments



### AWS Data

- Classification with Amazon Macie helps classify what data you have to determine what data is most important to back up frequently in accordance to RPO

- Data backups with AWS storage Gateway VTL, AWS Backup service



### AWS Elastic Disaster Recovery (AWS DRS)

- Ensures quick resumption of on prem and cloud based apps in the event of a disruption

- Based on continuous replication and launching recovery instances