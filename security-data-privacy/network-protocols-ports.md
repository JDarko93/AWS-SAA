## Network Protocols and Ports 

- TCP/IP is the most widely used network protocal suite 
- IPv4 uses a 32-bit address, split across 4 octets (8 bits/1 byte x 4)
- IPv4 addresses would map to OSI Model Level 3 (Network layer)

### IPv4 Addressing

- Each octet consists of eight binary bits
- Each octet falls between 0-255
- Octets ending in .0 usually means its a reference to a network address
- Octets ending in .255 usually means it refers to a broadcast address for a subnet where you send a transmission to everyone


### Reserved Private IPv4 Address rnages

- 10.0.0.0 to 10.255.255.255
- 172.16.0.0 to 172.31.255.255
- 192.168.0.0 to 192.168.255.255
- These were reserved to be used for private networks
- Internet networks wont route packets to destination IP address that fall within those ranges


### IPv6 addressing

- Eight Hextets (16 bit) separated by colons
- IPv6 uses 128 bit IP addresses
- Each hextet value falls between 0 and F
- 0-9 represent 0-9 as normal
- A represents the number 10, B = 11 etc all the way to F=15
- Colons (:) represent 4, 0s (absense of numbers)
- Examples FE80::69E8:36A8:269E:FCCF%24
- % is a network interface reference number 


### Common TCP Port numbers

- 22 Secure Shell (SSH)
- 25 Simple Mail Transfer Protocol (SMTP)
- 80 HyperText Transfer Protocol (HTTP)
- 442 HyperText Transfer Protocol Secure (HTTPS)
- 3389 Remote Desktop Protocol (RDP)


### Common UDP Port numbers

- 53 Client DNS query
- 67 DHCP server listening port
- 68 DHCP client listening port
- 161 Simple Network Management Protocol (SNMP)