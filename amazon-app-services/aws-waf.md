### HTTP Common Vulnerabilities and Exposures (CVE)

- These are common vulnerabilities thhat exist that allow access to systems
- CVEs have unique numbers asigned to them along withh the date it was found
- This list is constantly updated when new threats are found 


### Web Application Firewall (WAF)

- These are designed to intercept requests to HTTP based apps and APIs
- Protects from common threats such as SQL injection, cross-site scripting etc
- Uses OWASP Top 10 pre configured rules set
- Open Web App Security project (OWASP)


### AWS WAF Placement 

- Can be used to protect a custom app within an EC2 Instance
- Associate it with an API Gateway which serves as middle wear between API requests and responses
- Can associate it with a CloudFront distribution
- Can use it with an Application Load Balancer


### AWS WAF Features

- WAFs are designed to filter web based traffic such as IP addresses, Layer 4 TCP/UDP port number,s HTTP headers, HTTP bodys.
- This essentially is a Layer 7 firewall as it can look at the content of a given transmission or request
- WAFs have options for rate limits and blocking bot traffic
- Has fraud contorl, preventing login page attacks
- Has security metrics monitoring using CloudWatch 


### WAF Rules

- WAF configurations are centralised set of rules that can be applied to multiple web applications
- This means you dont have to recreate WAF configurations for each application
- You can add preconfigured rule sets to web ACLs such as account take over rule sets, bot control, admin protection, amazon IP reputation list to ensure known IP addresses are blocked


### AWS Firewall Manager

- In larger enterprise environment, multiple aws accounts will use AWS Filewall Manager to....
- Ensure compliance withh standard security rules
- Centrally manage multiple WAF deployments withhin or between AWS accounts