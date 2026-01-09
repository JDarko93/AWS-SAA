## Amazon Elastic Container (ECS)

- It allows you to run containerised applications in AWS
- It supports Docker 
- Manages app availability and scaling
- ECS clusters will recover unhealthy containers to ensure they are running


### ECS Features

- Intergrates with Amazon Fargate (Designed to handle the underlying compute capacity to run a workload)
- ECS Anywhere, allows you to use both cloud and on prem containers. Via AWS Systems manager, you can create a trusted relationship between your on prem and AWS cloud to run all containers
- Elastic Container Registry (ECR), this is a centralised repository of container images. They can be private or public
- Container version updates automatically managed