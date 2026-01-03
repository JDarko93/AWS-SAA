## Managing Route tables
- Route tables resources contain one or more routes, used to control network traffic flow to direct it to a certain location. Firewall applicance or gateway etc

## AWS Direct connect and AWS PrivateLink
- These are other methods to directly connect into the AWS cloud without connecting over the internet
- It allows customers to use a dedicated private network circuit for a single customer (1Gbps - 100 Gbps)
- Hosted connections stem from an AWS direct connect partner (50Mbps - 100 Gbps). This is when you use a direct connect partner within a region
- Direct connect allows for more predictable bandwidth compared to the internet
- Increased security compared to the internet due to the traffic not being sent over open public network infrastructure

### Direct connect configuration
- Have a router technition to configure your on prem router and be in contact with local provider to ensure circuit is provisioned
- Layer 2 OSI point to point connection (Data link layer) dealing with MAC addresses and the movement of Data
- You can split circuits in public and private interfaces

### AWS PrivateLink
- Similar to DirectConnect except connectivity is not just between on prem and AWS
- You can also interconnect VPC or even specific AWs resources and traffic still doesnt transfer over the internet
- Still different to VPC Peering because VPC peering opens up the entire VPC for communication using VPCs where as PrivateLink is to specific resources