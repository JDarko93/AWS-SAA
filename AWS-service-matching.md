## AWS Service Matching
- Business needs assessments to correctly match AWS services to business needs 
- Its important to be familiar with AWS services offerings as well as 
- Network requirements
- Storage requirements
- Compute rewuirements
- Monitorng and security requirements
- AWS service sprawl reduction, meaning checking older AWS services to make sure no old services are running in the background to save costs.

### Network requirements 
- How many VPCs do you need
- How many subnets so you need
- Do you need VPC peering, connecting VPC together to be able to talk to each other via a private connection rather than over the internet
- Are VPNs required for security reasons, like having engineers VPN into the web application from remote locations 
- Do you need to enable HTTPS using your own certificate or using AWS certificate manager
- Network / Threat monitoring using GuardDuty or CloudWatch network metrics to ensure everythhing is working well

### Compute requirements 
- Do you need to manually deploy EC2 instances or can you automte the amount of EC2 instances and types are deployed via 
- Will there be a need for ECS ECR or EKS to manage application containers in a centralised way

### Storage requirements 
- Do you need S3 bucket object storage
- Or do you need database storage, NoSQL or SQL based. NoSQL meaning less structured database but more used in large scale data sets
- Security such as using Amazon Macie data classification and server side encryption or client side encryption as well as customer managed keys 

### Monitoring and security
- Cloudwatch monitoring to keep 
- CloudTrail auditing to audit any changes made that might have been unauthorised
- Amazon Detective which is used to investigate security incidents
- NACLS to control access to your network level
- Security groups to control access to your EC2 level
- WAF to control traffic into your network 
- Security standards compliance - PCI DSS, GDPR to heklp stay regulated 