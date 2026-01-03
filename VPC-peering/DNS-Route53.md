## DNS and Route 53 
- DNS in its simplest form is a name resolution service. For example www.google.com > 142.250.140.104 (equivalent IP address)
- This is name resolution for both IPv4 and IPv6

### DNS Zones
- This initially was a file that contained all DNS records for that zone
- Records that would resolve to IPv4 addresses

### DNS Recursion
- This is when a DNS server that receives a client query to resolve a name is incapable of solving it
- It reaches out to other DNS servers to see if another server can resolve the name

### DNS caching
- Occurs both at DNS server level for successful resolutions and also on client devices
- It has TTL (Time To Live) to determine how long they stay cached

### Fully qualified Domain Name (FQDN)
- This is a full entire name
- Like www.google.com
- .com (Top level domain) there are DNS route servers responsible for top level resolutions
.google (second level or sub domain) this is the part of the domain that is registered
www. (Host) this is the DNS record within that zone which resolves to a IPv4 address
- FQDN can resolve to an IPv4 address using DNS "A" or IPv6 using "AAAA"
- IPv6 addresses are 4 times longer than IPv4
- IPv4 addresses are 32 bits 
- IPv6 addresses are 128 bits

- DNS Domain names is just a string of text
- DNS zones contains the information about the domain name

### DNS Record types
- A -Resolves FQDN to an IPv4 address
- AAAA - Resolves FQDN to an IPv6 address
- CNAME - Alias records which points to the domain name (Not the IP address) if you have multiple names for the same IP address
- MX - Mail exchange record used for STMP transfer between mail servers
- PTR - Pointer record used to reverse lookup record. When you know the IP address and need to know the Domain name
- TXT - Less commonly usedStores arbitrary text data.


### Amazon Route 53
- Managed DNS service meaning no neet to deploy VMs
- Its a name resolution service for AWS services like private DNS names aswell as services outside of AWS
- You can register new domain names 
- You can also transfer existing domain names you own to AWS to manage
- You can host DNS zones using Route 53

### Route 53 Health Checks
- Supports DNS health checks to check application reachability verifications
- Endpoint connectivity using TCP, HTTP or HTTPS
- Ensures traffic is not routed to unhealthy endpoints that dont respond to the connectivity test