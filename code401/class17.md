# Read17: AWS: API, Dynamo and Lambda

## Research:
1. What’s the difference between a FIFO and a standard queue?
   - [Standard](https://jayendrapatil.com/aws-sqs-standard-vs-fifo-queue/) queue: guarantee that a message is delivered at least once and duplicates can be introduced into the queue
   - FIFO queue: ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.
  
2. How can the server be assured a message was properly received?
3. What classic design pattern is best represented by event driven programming?
   [Observer pattern](https://en.wikipedia.org/wiki/Observer_pattern)

4. How do you test an event driven system?
    > The biggest difference between testing synchronous applications and those that are based in event-driven architectures is having to accommodate the asynchronous nature of the interactions. Developers still have to unit test. Integration testing still needs to be done, as does performance and deployment testing.


## Vocabulary:

|  Vocabulary | meaning                          |
|---------|----------------------------------|
| Serverless Functions | is an event-driven function that have a cloud computing execution |
| Cloud Storage | It is an online storage that saves and protects your data, like OneDrive or google drive |
| CDN | Content Delivery Network, is a highly-distributed platform of servers that helps minimize delays in loading web page content by reducing the physical distance between the server and the user |






## Review:
### AWS API Gateway
* A service provided by AWS.
* used to create, publish, maintain, monitor, and secure APIs at any scale.
* It deals with REST, HTTP, and WebSocket APIs.

![](https://d2908q01vomqb2.cloudfront.net/1b6453892473a467d07372d45eb05abc2031647a/2018/06/13/edge-optimized-1024x513.png)


### AWS DynamoDB
* A NoSQL database service provided by AWS.
* Supports key-value and document data structures.
* Highly secure, it encrypts at rest all user data stored.
* uses hashing and B-trees (self-balancing tree data structure) to manage data.
* It is Serverless.
* > Dynamoose is a modeling tool for Amazon's DynamoDB (inspired by Mongoose) NPM.

### AWS DynamoDB vs S3:

![](https://qph.fs.quoracdn.net/main-qimg-c9730a6b44f977087686b5a7cb02fbaa)



## Resources:
- [Dynamoose](https://snyk.io/advisor/npm-package/dynamoose)
- [API gateway](https://www.serverless.com/amazon-api-gateway)
- [DynamoDB](https://www.dynamodbguide.com/what-is-dynamo-db/)


