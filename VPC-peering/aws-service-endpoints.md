## AWS Service endpoints
- This is the URL for the entry point into an AWS service like DynamoDB, S3 etc
- Allow programmatic API/CLI connectivity to a service using a URL
- Some services such as DynamoDB use regional endpoints. For example. https://dynamo.db.us-east-1.amazonaws.com. This is when the region is referenced within the URL
- Some services like IAM have endpoints that dont reference the regions like IAM. https://iam.amazonaws.com. 
- Some AWS services such a EC2 support endpoints with and without regions 
- Some AWS services in specific regions support Federal Information Processing Standard (FIPS) endpoints which require at least TLS 1.2 HTTP connections for compliance 

### VPC Endpoints
- Purpose of this is to allow access to AWS services not configured with public internet access
- This is different to VPC peering

### VPC Peering vs VPC Endpoints
- VCP Peering allows direct inter-VPC connectivity to all resource types
- VPC Endpoints allows direct connectivity to specific resource with endpoints configured 

- Peering requires the creation of route table entries
- Endpoints dont require route table entries 

- Peering IP address range between peered VPCs and cannot overlap
- Endpoints IP address range overlap is not an issue 


### VPC Endpoints types

#### Interface 
#### Gateway load balancer
#### Gateway 

- Interface and Gateway load balancer is through AWS private link meaning the traffic doesnt leave AWS private networkß