## VPC Peering
- Allows us to link VPCs directly together
- Connect within AWS account or different AWS accounts
- You can peer them within same or different regions also
- They connect via a private network using their private IP address
- Peering connections are not transitive, meaning you dont automatically have access to vpc3 from vpc1, if vpc1 is connected to vpc2 and vpc2 connected to vpc3

### Configuring VPC Peering
- Begins with creating VPCs and subnets 
- Create peering configuration
- The target VPC would have to accepted the peering request
- Adjust route tables for both peered VPC by adding the network range of the CIDR block of the other VPC into the route table of a peered VPC
- The configuring the route table, the target would be the peering VPC ID