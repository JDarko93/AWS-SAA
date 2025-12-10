## AWS Cloud computing shared responsibility
- Responsibility varies from one service to another (IaaS, PaaS, SaaS)

### Infrastructure as a Service (Iaas)
- Customers manually deploys services such as S3 buckets, EC2 instances etc
- For VMs customer is responsible for the OS, its configuration, apps and patching
- For VMs, Amazon is responsible for the underlying hardware and hypervisors

### Platform as a Service (PaaS)
- These are things like databases
- Customer deploys managed platform such as Relational Database Service (RDS)
- The customer would be responsible for the data ON the platform where AWS would be responsible of the underlying infrastructure that ensures the database can continue to run
- Things like the actual compute power, switches etc

### Software as a Service (SaaS)
- Customer deploys or develops high level software ready to use
- Customer is responsible for limited configurations. For example GMail is google SaaS software which is ready to use out of the box to access emails

### Service level agreement (SLA)
- Service level agreements provides details on guaranteed uptimes for services. If they are not met then the service provider will offer credits off their next service bill
