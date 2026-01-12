## Examining network traffic

- In AWS you have the option within the VPC management console to configure traffic mirroring
- Start by selecting Mirror source such as Elastic Network Interface (ENI)
- Then select the mirror target like another ENI or ELB or Gateway LB endpoint
- Specify maximum number of bytes you want to capture 
- Filter by the types of traffic you want to mirror
- Port range, IP address CIDR blocks + more