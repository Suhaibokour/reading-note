# AWS: Events

## Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
* Express is a web framework for Node.js . It simplifies the development of “serverless” web sites, web applications, and APIs. In a serverless environment, most or all of the backend logic is run on-demand in a stateless fashion (see Mike Roberts’ article on Serverless Architectures for a more detailed introduction). AWS Lambda, when used in conjunction with the new Amazon API Gateway features that I blogged about earlier this month (API Gateway Update – New Features Simplify API Development), allows existing Express applications to be run in serverless fashion. When you use API Gateway you have the opportunity to take advantage of additional features such as Usage Plans which allow you to build a developer ecosystem around your APIs, and caching which allows you to build applications that are responsive and cost-effective.

### List the AWS Database offerings and talk about the pros and cons of each:
* Purpose Built
* Performance at Scale
* Fully Managed
* Secure & Highly Available

---


### What’s the difference between a FIFO and a standard queue?
* Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.

### How can the server be assured a message was properly received?
* Logging and using timestamps and checking whether it was delivered based on the response sent from the endpoint.

### Serverless API
* Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provider

### Triggers
* Essentially a connection between resources. When something happens to a resource, it triggers an action to be taken.

### Dynamo vs Mongo
* MongoDB is one of the most famous documents oriented database whereas DynamoDB is scalable, hosted NoSQL database service provided by Amazon with the facility to store the data in Amazon's cloud. ... Mongo database offers some API for user-defined Map/Reduce methods, whereas Map Reduce is not supported in Dynamo database. Dynamo is like the AWS version of Mongo. Mongo is open source and uses JSON objects, whereas Dynamo uses tables. MongoDB is less restrictive of data types and size.

### Dynamoose vs Mongoose
* Dynamoose is a modeling tool used for dynamo and mongoose is used for mongo.

---
### AWS SQS vs SNS

* SQS :Simple Queue Service SQS is a fully managed message queuing service. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available. Messages are not pushed to receivers, receivers have to poll or pull messages from it. Messages can’t be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later.
* SNS: Simple Notification Service SNS is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. Messages are pushed to subscribers as and when they are sent by publishers to SNS (immediately), unlike in SQS where polling inherently introduces some latency in message delivery.



