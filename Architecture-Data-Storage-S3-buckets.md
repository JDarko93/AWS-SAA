## AWS Global Infrastucture

- Consists of 200+ IT available
- All accessible over the internet and hosted on AWS hardware and physical servers
- Scalable infrastructure
- AZ / Regions split up globally allowing for move availability of services
- Network latency if an issue can be helped with by edge services 
- Network security is also available like HTTPS connectivity and ability to directly launch VPNs directly from AWS
- AZ = 1 or more data centres within a region

### AWS Data Centers
- HVAC (Heating, Ventilation and Air Conditioning) are all needed in data centers to be able to correctly host and run the physical servers, switches etc
- Physical security such as guards, perimiter fencing, security cameras, physical authentication etc is also vital 
- Locations, construction details, equipment being used, storage media destruction techniques are kept private for security reasons

- Data centers HVAC uses reclaimed water where possible for cooling rather than drinking water
- AWS is developing their own power sub stations and water treatment facilities to help run all their physical systems


### AWS Network Connectivity 
- We can use VPN connections over the internet to connect directly into AWS services to access them via an encrypted tunnel
- Direct connect is a private dedicated network circuit that allows direct connection to AWS services without connecting through the internet. 
- AWS services talk to each other this way