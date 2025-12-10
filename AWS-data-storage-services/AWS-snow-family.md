## AWS Snow Family
- Can be used to import large amounts of data into AWS or out of AWS
- There are 3 types of hardware devices for the snow family

#### AWS Snowcone
#### AWS Snowball
#### AWS Snow mobile

### AWS Snowcone
- Smallest version of the snow family. It is a rack-mountable device used for storage
- Comes in SSD (14TB) or HDD (8TB)
- Data copied to the device via an NFS mount point
- Offline data transfer via physical device shipping / using AWS DataSync which is pre installed
- 256-bit encryption for protection of data at rest
- Anti-tampering via Trust Platform Module (TPM)
- Secure erasure of data on the device after job completion using NIST guidelines to ensure no artifacts left over that could be used be another user

### AWS Snowball
- Edge compute optimised option to process data locally on prem using AWS Lambda code
- It does what SnowCone can do but it can also has the ability to run compute analysis on the data
- Download SnowBall edge client to unlock the device once its powered up
- Copy on prem data to the device using S3 GUI or an NFS Mount point

### AWS SnowMobile
- A physical truck to transfer data at extremely large scale like transferring data for a government agency

