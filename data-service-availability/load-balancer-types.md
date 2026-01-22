## AWS Load Balancer Types

- Load balancing allows for increased application availability due to multiple options of backend servers

- Improves performance also due to multiple options of servers

- When defining a LB it can be public or private facing 

- Clients are directed to a load balancers interface. Then the load balancer then distributes the requests to the backend servers



### AWS Load Balancer Types 


### Application Load Balancer
- OSI layer 7 (Application layer), HTTP, HTTPS

- Application load balancer can look at details within the URL or direct client requests

- Supports TLS (Transport Layer Security) offload lessens backend instance compute workload.

- Works with WAF which is designed to mitigate HTTP specific web attacks


### Gateway Load Balancer

- OSI Layers 3/4 (Network & Transport layer) IP address, port numbers

- Designed to work with 3rd party virtual appliances like IDS or firewall appliances to distrubute load to them


### Network Load Balancer

- OSI layer 4 (Transport layer), TCP/UDP port numbers

- Accepts connections on load balancer listening interface for example port 443 for HTTPS and forwarding it to web servers to backend target group



### Web Application Firewall (WAF)

- Is an OSI layer 7 firewall. It looks at packet headers for MAC addresses, IP addresses, Port numbers but can also look at payload to see what is in the request to a web app

- Its based on OWASP (Open Web Application Security Project) rule sets

- OWASP is a collection of volunteers whos sole focus is to enhance the security of web apps

- OWASP top 10 vulnerabilities list is updated annually