## Amazon Serverless Compute
- Managed services (PaaS). You dont manage the underlying infrastructure
- They automate instance deployment and management

### Amazon Batch
- Long running jobs to manipulate data in an automated fashion
- Compute and memory power adjusted manually or automatically
- Jobs are scheduled to run on EC2, spot instances or Amazon Fargate

### Application containers
- App code and dependencies are packaged into a container
- An entire app or app microservice runs in the container
- ECS / ECR / EKS

### Amazon Fargate
- This is a serverless engine for app containers
- Fargate focuses on the underlying compute infrastructure for containers
- EKS is a container orchestration solution at the container level
- ECS is a serverless service that allows you to run 1 or multiple containers and host in the cloud

### Amazon Elastic MapReduce
- Managed cluster platform that allows distributed processing
- Distributed processing means you have very complex or large jobs or both that are too much to run on a single server so it spreads out over multiple servers
- It allows for big data analysis
- EMR is designed to be integrated with EC2 or EKS
- Based on Apache Hadoop which is a Java solution designed for distributed processing of large datasets across multiple servers