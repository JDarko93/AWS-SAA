## Public Key Infrastructure (PKI)

- Is a hierarchy of digital security certificates (Chain of trust)

- Certificates are issued by certification authority (CA) which is at the top of the hierarchy

- If a device trusts a private CA thats been configured. By default, that device will trust all certificates issued from that CA at any level

- If a device only trusts a sub CA, it will only trust devices from the sub CA

- There is a trust list of Public CAs within the OS. So when you connect to a HTTPS website such as online banking, and the bank has a certificate digtially signed by a public CA, your device will trust that banks certificate, because it trusts the public CA

- With private internal CAs you have to install the root certificate on that specific device to allow trust those certificates


### PKI Certificate issuance

- Certificates can be issued to individual users via email
- You can issue PKI certificates for devices. It might contain the Fully Qualified Domain Name (FQDN) for that device or website
- You can issue PKIs to software entities. Software can partake in whatever is required cryptographically


#### Wildcard certificates 

- *.mydomain.com. This means 1 certificate that applies to all websites that end in mydomain.com

- Extended domain validation, enhanced CA due diligence against certificate requester

- Code signing certificates



### PKI Certificate LifeCycle

1 - Certificate signing request (CSR) - Generating a public and private key pair and then submitting those details with company name or username or email or website FQDN. Once this is validated, the CA will issue a certificate

2 - Issuance. Certificate is issued

3 - Once issued it can be used for encryption, decryption, digital signing etc.

4 - Once we dont want to use it anymore it can be revoked. For example an employee has left the company and the PKI is no longer required or compromised. Otherwise it can be used until its expiry date.

5 - Renewal / Expiry. You can renew certificates before the expire but once expired you can not renew them again


### Certificate templates

- Used when issuing certificates

- They can include details such what encryption will be used, what signing algorithm will be used

- Use certificate usage constraints



### PKI Certificate content 

#### Subject names 

- User would be an email address
- Website would be a FQDN or IP address

#### Certificate usage

#### Issuing CA, CA Signatures

- Unique digital signatures from the CA used to ex
establish the chain of trust

#### Public key (private key kept in OS secret secure store)

- This validates the CA public key verifying a signature requires a private key

#### Issue and expiry date

#### Many other attributes


### Revoked certificates

- Certificate revocation list (CRL) are entire lists of revoked certificate serial numbers. This can be downloaded from the CA and the list can be checked locally

- Online Certificate Status Protocol (OCSP). Each certificate validity is checked as it is being used. You dont need to download the entire list of revoked certificates