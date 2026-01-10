## AWS Security concepts

- Amazon compliance with numerous security standards like HIPPA, NIST, GDPR
- Shared responsibility - cloud customers must also conside security options in their deployment


### AWS Security

#### Defense in depth

- Having multiple levels of security at network level
- Network ACL
- Security groups


### Principle of least privilege (PoLP)

- Granting the least possible permissions to perform a task


### Network encryption

- All AWS global network traffic is encrypted from the physical data layer
- VPN from on prem to AWS
- HTTPS / TLS (Transport Layer Security) 1.2 to AWS services
- TLS 1.2 or higher is used on client side as anything under that has known vulnerabilities


### Encryption of data at rest

- Default Server Side Encrpytion (SSE) with Amazon S3 is enabled using AWS managed keys (SSE-S3)
- You can also create keys via Key Management Service (KMS) and use custom keys (SSE-KMS) to encrypt S3
- Can set default bucket encryption for new objects
- RDS Advanced Encryption Standard (AES) database using 256-bit encryption
- Oracle and Microsoft SQL server Transparent Data Encryption (TDE)


### AWS User Accounts

- In AWS the first account is the Root User
- You can create further accounts (IAM users), groups and policies that then have desired access levels for resources, services
- Use MFA for user sign in security for added protection


### AWS Shield

- This protects against DDoS attacks
- This is when multiple infected computers / bots attack specific hosts or network by flooding it with a high amount of requests 
- It integrates with AWS WAF, CloudFront, EC2, Route53
- Standard is enabled by default
- Advanced allows you further insights into the traffic to give you a closer view of what is happening