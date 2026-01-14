## AWS Federated access

- Uses a centralised trusted authenticator

- Authentication capabilities are removed from apps

- Apps rely upon the trusted authenticator

- A trusted authenticator can span multiple apps


### Trusted third-party authentication

- Like sign in with google, facebook etc


### Identity and resource providers 

- An identity provider (IdP) is on prem or cloud based 

- A resource provider (RP) service provider (SP) is an app that trusts the IdP



### Identity federation claims

- Are assertions about a user or device

- Contained within a digitally signed security token and are then consumed by apps

- Claims include, DoB, subnet IP, security clearance level, email address etc

"Claims" are considered to be a form of attribute-based access control (ABAC)



### AWS Identity solutions

- Single Sign-On (SSO)

- AWS Security Token Service (STS)