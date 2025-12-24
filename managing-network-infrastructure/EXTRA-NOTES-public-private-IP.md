## Public vs Private IP (IPv4)

- The internet assigned numvers authhority (IANA) establishes certain blocks of IPv4 addresses for the use of private (LAN) and public (Internet) addresses

### Private IP

- These can only allow certain values

#### 10.0.0.0 - 10.255.255.255 (10.0.0.0/8 subnet mask) = BIG Networks
#### 172.16.0.0 - 172.31.255.255 (172.16.0.0/12 subnet mask) = AWS Default VPC in that range
#### 192.168.0.0 - 192.168.255.255 (192.168.0.0/16 subnet mask) = LAN networks like home networks

- Rest of the IP addresses on the Internet a public IPs 