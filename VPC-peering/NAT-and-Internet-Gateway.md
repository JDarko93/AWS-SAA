### NAT gateways & Internet gateways
- NAT gateway is a managed service meaning we make small configuration settings and something happens to allow instances that dont have public IPs to get access to the internet
- NAT gateways will let instances with private IPs out to the internet but will not allow requests coming from the internet into the private instance
- If you want incoming requests from the internet to gain access to your instances you will need an Internet Gateway
- Internet gateways allow access to and from the internet
- NAT gateways are private as it cannot be reached from the internet

### Internet Gateway
- Egress only Internet gateways only allow outbound IPV6 traffic to the internet
- Similar to the NAT gateway as it only allows outbound traffic but NATs are only for IPV4 traffic to the internet