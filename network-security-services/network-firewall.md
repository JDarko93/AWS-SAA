## AWS Network Firewall

- This is a managed service that gives us firewall capabilities which is stateful. So it watches the state of a session 

- Has intrusion prevention component, supports web filtering and bad URLs

- Ability to create rule groups or import rules

- AWS Firwall manager allows you to manage multiple firewalls centrally


### Firewall rule groups

- They can be either stateful or stateless

- Firewall rule groups once configured get added to Firewall policies


#### 3 rule group options

- 5-tuple: Uses source IP, source port, destination IP, Port and protocol types. Standard Layer 4 packet filtering type of rules based on packet headers 

- Domain list: AWS resources trying to reach certain URLs or domains which you can either allow or deny 

- Suricata compatible IPS rules: Designed to look for anomalies that indicate network security problems and stop them in their tracks