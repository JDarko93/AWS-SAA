## Amazon Application Development Services

- Serverless = managed service where we dont manage the underlying infrastructure


### Amazon Simple Queue Service (SQS)

- This is a messaging service in the cloud, allowing software components to send, store and read components
- Enables app component decoupling
- Provide standard of FIFO (First In First Out) queues
- Standard Queues are best for large volumes of messages
- FIFO Queues are processed only one time in the order it was sent into the queue.
- Differen applications would need a different type of queue


### AWS Lambda

- Serverless cloud service that runs code (Java, Go, PowerShell, Node.js, Python, etc)
- Write code in the lambda console
- Upload a code.zip file or container image
- Code is triggered by an event. Events like a web link being clicked, new database record being created, file uploaded to S3 bucket etc


### AWS API Gateway
- Scaleable serverless solution that can process API calls
- API Gateway acts as a middle man between a service or client that makes a call to the API, and the API itself
- Supports API authorisation and access control
- Also deals with traffic management and throttling to limit the amount of API calls being made within a timeframe


### Amazon Cognito

- Allows developers to ad user sign-up and sign in functionality to an app
- Its scaleable and supports numerous identity providers like google, facebook, amazon, apple etc