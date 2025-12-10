## AWS Well architected Framework
- 6 Pillar design principles for cloud-based IT systems
- This ensures that the use of AWS cloud services is done in the correct, most efficient and effectively as possible

#### Operational excellence
#### Security
#### Reliability
#### Performance efficiency
#### Cost Optimisation
#### Sustainability 


### Operational excellence
- This is about monitoring deployed services to ensure peak efficiency and utilisation 
- This is done via AWS CloudWatch that monitor services to give us notifications if there are any anomilies in any used AWS services 

### Security
- This deals with data confidentiality. Encryption in transit and at rest
- Ensuring Principle of least priviledge
- CloudTrail auditing for example helps with data integrity to ensure data hasnt been tampered with
- IAM users, roles, policies and threat detection solutions are all also involved in this security pillar to ensure proper use of CIA triad 

### Reliability 
- Distributed services into  multi-AZ/region deployment allows for more reliability by reducing a risk of any downtime due to an AZ or region failure
- Disaster recovery plans (DRP) are important for each aspect of a system. For example, a web app used by end users and internal data base used by employees should all have DRP in place to allow for quick recovery due to any disruptions
- Ability to scale our or in when needed due to rise or fall in demand

### Performance efficiency 
- Matching service sizing to workload requirements
- The ability to have the correct amount of compute power to allow your systems to run well

### Cost optimisation
- This is removing unused resources
- Save cost for any unused services
- Also using the most efficient services available. For example using spot instances rather than reserved intances 
- Cost budget alerts in place to ensure no surprise peaks
- Monitoring usage and performance metrics to being able to maximise usage of any compute power as you pay for what you use

### Sustainability
- AWS uses renewable water, power
- Customers to use what is required to smoothly run their services for their clients and not over using anything as this will cost you and AWS more due to maintainance and service costs 