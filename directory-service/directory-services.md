## Directory Services 

- A centralised network configuration database thats hosted on one or more servers

- Microsoft Active Directory Domain Services (AD DS) stores settings for users, groups, devices, apps

- A domain controller in this environment is a microsoft server that has a copy / replica of the AD DS database 


### AWS Simple AD

- Its not true Microsoft AD - uses Samba 4 compatible directory service

- It supports small (2000 directory service objects) and large (20k objects)

- Does not support MFA, domain trusts, PowerShell AD Recycle bin

- If you dont need the above features, the AWS Simple AD may be the right fit 


### Directory types

- AWS Managed Microsoft AD
- Simple AD
- AD Connector
- Amazon Cognito User Pools


#### AWS Managed Microsoft AD

- Is Microsoft AD DS, but hosted and managed by AWS

- Uses standard AD management tools

- Join EC2 and RDS instances and physical hosts to the domain


##### Standard and Enterprise options 

- Standard has 1GB storage
- Enterprise has 17GB storage

- Standard optimised for 30k objects
- Enterprise optimised for 500k objects

- Cost difference for standard / enterprise



#### AWS AD Connector 

- Links existing on-prem AD to AWS

- Cloud directory requests are sent to on prem AD

- One connector config is required for each on prem AD domain

- Users continue to use existing credentials even when accessing cloud resources