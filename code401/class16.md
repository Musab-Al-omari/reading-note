# Read17: AWS: S3 and Lambda

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
| Server Instances | A server instance is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. |
| Containers | is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. |
| Cloud Services | a wide range of services delivered on demand to companies and customers over the internet. |
| Cloud Architecture |  is a de area network (WAN) over the Internet. |
| AWS | Amazon Web Services |

### EC2/Beanstalk vs Heroku
![](https://miro.medium.com/max/1390/1*3VABrNh8HjoJnTST_hMknQ.jpeg)

## Review:
### AWS S3
* S3 stands for Amazon **Simple Storage Service**.
* As the name suggests, it provides storage over the internet where you can store and secure your data.
* designed to make web-scale computing easier for developers.
* It offers industry-leading scalability, data availability, security, and performance.

### AWS Lambda:
* It is a service which computes the code without any server.
* It is an event-driven serverless compute service.
* Use mostly Node JS and Python.

![](https://hackernoon.com/hn-images/1*QouD2Gm74jIG4mRMXlk5cQ.png)

## CDN:
* CDN stands for Content Delivery Network (or Content Distribution Network)
  > A Content Delivery Network (CDN) is a highly-distributed platform of servers that helps minimize delays in loading web page content by reducing the physical distance between the server and the user. 

![](https://hackernoon.com/hn-images/1*cCDDf6wVCPSOvslnXvkrmw.png)

## Resources:
- [Server Instances](https://www.techopedia.com/definition/32149/server-instance#:~:text=A%20server%20instance%20is%20a,based%20or%20command%2Dline%20based.)
- [Containers](https://www.docker.com/resources/what-container)
- [Cloud Services](https://www.citrix.com/en-in/glossary/what-is-a-cloud-service.html)





