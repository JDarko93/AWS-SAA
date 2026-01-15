## Network Access Control Lists (ACLs)

- This is a packet filtering firewall solution that decides what traffic to allow or deny access to your subnet
- Looks at source/destination IP address
- Source / destination port number
- Protocol type - TCP, UDP, ICMPv4, ICMPv6, custom

- Network ACLs are associated with subnets 
- Create in/outbound rules withhin the NACLs which have priority numbers
- Priority numbers are used to determine the order that the rules get processed in
- Ability to create allow rules
- Ability to create deny rules


### NACLs / Security Groups

- When it comes to inbound traffic, NACLs are checked before security groups for the EC2 instance
- With outbound traffic, the security group is checked before the NACL