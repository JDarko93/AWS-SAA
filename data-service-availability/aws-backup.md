## AWS Backup

- Managed service that offers backup for AWS services in the event of a mistake such as data corruption

- Centralised cloud backup using AWS backup console and command line tools

- You can either back up automatically or on a schedule

- Protected resources are backed up items that are stored in a backup vault

- Each backup vault has a vault access policy to control who can do what regarding backups and restores


### AWS Backup Sources

- AWS backup is natively integrated with S3 and works with EC2 instances, EBS voluments, RDS databases, DynamoDB tables, EFS file systems, Store Gateway volumes


### AWS Backup policies

- Back up plans allow you to schedule frequency of backups which should be in like with RPO (Recovery point objective), encryption and which key is used

- Backup retention, how long backups should be kept for. These are based off regulations

- Backup lifecycle management for example moving backups to cold storage over a period of time