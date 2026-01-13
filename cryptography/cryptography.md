## Cryptography & AWS Security

#### Symmetric encryption

- One key. This is when it uses 1 key to encrypt but also to decrypt. Other wise known as a secret key

#### Asymmetric encryption

- Two keys. You get a key pair public and private key that are related mathematically. The public key is used to encrypt and the private key is used to decrypt

### Encryption - CONFIDENTIALITY

- Plain text - Is when the data is in its original form
- Ciphertext - Is when the data has been encrypted using a key + algorithm. Returning scrambled text


### Hashing data - INTEGRITY

- This ensures data integrity for messages
- Provides a secure method of storing password
- Use hashing to detect file system modifications
- Can be used with encryption for confidentiality, integrity and message authentication
- Hashing isn't reversible like encryption is as there are no keys involved

- Hashing works by running the data through and algorithm which generated a hash. This is compared to the next time to the data is run in an algorithm to determine if anything has changed.


### AWS Key Management Service (KMS)

- Cloud based service that integrates with many AWS Services that require keys
- You can generate keys in AWS KMS
- MESSAGE AUTHENTICATION CODES (MAC)


### Cryptography and Storage

#### Self-encrypting drive (SED)
- This provides protection for data at rest without requiring any external required apps in the OS

#### OS encryption

- Windows encryption file system (EFS) which is within the Windows OS and allows you to encrypt individual files and folders

- Microsoft BitLocker, this is tied to the machine and encrypts entire disk volumes rather than individual files

- AWS S3 bucket encryption, which automatically encrypts anythhing uploaded into an S3 bucket

- ECR container image encryption

- AWS RDS database replicas encryption

- Some database solutions have built in encryption built in for data at rest. This is called Transparent Data Encryption (TDE) which is on Microsoft SQL Server


### AWS and Encryption

- AWS Certificate manager (ACM) to generate PKI digital security certificates which also generate public and private key pairs

- AWS Key management Service (KMS)

- S3 bucket encryption using AES 256

- VPN encrypted tunnels

- HTTPS encrypted connections