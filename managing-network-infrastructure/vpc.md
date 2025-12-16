## VPC & Subnets
- VPC = Virtual private cloud
- In AWS VPCs can be allocated in IPV4 or IPV6 CIDR Block
- CIDR = Classless Inter Domain Routing
- Its a method of specifying the bits in a subnet mask with the /notation for example /24

### VPC Configuration 
- Subnets belong to a VPC and its IP address range is derived from within the VPC IP address range 
- DHCP option contains a number of configuration settings for that VPC and subnets for things like DNS resolutions
- NACL = Network Access Control Layer. A NACL acts similar to a layer 4 firewall which controls access at the subnet level for what goes in and what goes out of the subnet. These are done by rules
- Route tables control network traffic flow
- You can assign up to 50 tags

### VPCs and DNS
- DNS name resolutions enabled by default. For example if you deployed VMs in a subnet within a VPC, they will be able to resolve internet names to IP address
- You can specify custom DNS server entries, for this you need to create a new DHCP option set for your VPC