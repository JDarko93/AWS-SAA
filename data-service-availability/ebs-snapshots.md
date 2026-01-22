## Elastic Block Store Snapshots

- These are separate resources you can create and attach to EC2 instances

- EBS Volume snapshots are point in time pictures of the state of that EBS volume, which you can revert to or even copy to another region

- Snapshots are not encrypted if the source EBS Volume isnt encrypted

- Copying snapshots to different AZ~ is also a good form of high availability