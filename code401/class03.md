# Readings: Express REST API


# Q1 Name 3 real world use cases where you’d want to change the request with custom middleware


#### Transaction management: 
Middleware can be used to manage and control individual transactions and ensure that any problems do not corrupt the system or database.
#### Application server:
 Middleware can be used to host an API, allowing other applications to access and use the main application’s business logic and processes.
#### Security: 
Middleware can be used to authenticate client programs and confirm that the program and the user behind the program are actually who they claim to be.
Message queues: Middleware can be used to pass messages between different systems or software. The messages can then trigger a transaction or other action.
#### Directory:
 Middleware can be used as a directory, enabling client programs to locate other services within a distributed enterprise.
#### Web server:
 Middleware can also accept client requests from web browsers and channel them to the main server/database and then deliver the responses to the browsers



 # Q2 True or false: The route handler is middleware? 
 TRUE 

 # Q3 In what ways can a middleware function end the process and send data to the browser?

USING NEXT function with or without argument 
with: it will call another middleware which is error handler
without: it will invoke the next function which is the route 


# Q4 At what point in the request lifecycle can you “inject” middleware?
between the route and the Handler function or we can make it globle by puting in  as a first line of routs 

# Q5 What can cause express to error with “Request headers sent twice, cannot start a second response”
when you  try to send r response to the clint like this example 
```
const express = require('express');
const bodyParser = require('body-parser');
const app = express();

app.use(bodyParser.json());

app.post('/test', (req, res) => {
  if (!req.body.name) {
    res.status(400).json({
      status: 'error',
      error: 'req body cannot be empty',
    });
  }

  res.status(200).json({
    status: 'succes',
    data: req.body,
  })
});
app.listen(4000, () => {
  console.log('Server live');
});



```




# tearm 

* Middleware:
  Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system. Data management, application services, messaging, authentication, and API management are all commonly handled by middleware.
* Request Object 
  The Request object retrieves the values that the client browser passed to the server during an HTTP request.
* Response Object :
  It is the object which communicates between the server and the output which is sent to the client
* Application Middleware
   middleware that works on application level 
* Routing Middleware
   middleware that works on route level 
* Test Driven Development :
Test-driven development is a process of modifying the code in order to pass a test designed previously. In Software Engineering, It is sometimes known as "Test First Development." TDD includes refactoring a code i.e. changing/adding some amount of code to the existing code without affecting the behavior of the code.
  
* Behavioral Testing
  Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.