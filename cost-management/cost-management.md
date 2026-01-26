## AWS Cost Management

- Spot instances, these instances allow you to set a maximum price you're willing to pay for running VMs, and if there is spare compute power available at that price, you will be able to used them. They are not recommended to run mission critical services due to the compute capacity not being guaranteed

- Reserved instances, ability to lock in from 1-3 years for 24/7 usage of EC2 instances based on a region and instance type. Matching instances within the region or instance type will be within the reserved instances, up to the amount previous purchased

- Savings plans, ability to save money on EC2 instances on a per hour basis over a longer period of time. V reserved instance which is a only up to your budget amount

- Monitoring of usage and unused resource is also very important to ensure they are being used correctly 

- Monitoring performances, maximise use by resizing instances or change instance type 


### AWS Instance Scheduler

- Configure EC2 and RDS instances to start and stop on a schedule

- Custom tags is how the scheduler knows which instances to start or stop

- Instances when stopped are in hibernation mode so when they're started again the will start back up from where they left off


### AWS Pricing calculator

- Gives you the ability to see the estimated costs for resources before deploying them


### AWS Cost Explorer

- Gives you a break down of how much your resources have costs you over a specific time span


### AWS Budgets

- Cost budget, this gives you alerts when your monthly spend hits its threshold

- Usage budget, gives you alerts when you've hit your usage limits that you have set

- Savings plans budget, lets you see how your savings plans you have configured to commit per hour is being used

- Reservation budgets, alerts when your reservation usage doesnt hit the limits you've set