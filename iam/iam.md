## AWS Identity and Access Management (IAM)

- Deals with getting users, devices, software authenticated to AWS and having the right access to resources they need through permissions assigned
- Users are created, users can be in groups if multiple users need the same access permissions
- Roles is when you give access to a service or software to be able to speak to another


### Authentication and Authorisation

#### Authentication
- This is proof of identity 
- Single factor (Something you know) is Username and password
- MFA (Something you know and have) - is username password and smart card for example

#### Authorisation
- This kicks in after successful authentication
- Controlled access to apps and AWS resources
- Policies are collections of permissions
- Ability to create custom policies and assign to users, groups and roles