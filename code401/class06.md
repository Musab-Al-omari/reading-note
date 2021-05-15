# Readings: Authentication


### explain what a “Singleton” is (in Computer Science terms)
singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.

### Explain how the Singleton pattern can be used with Node modules, specifically with classes
we will create 2 classes , first one we will call it privit singleton and inside it we will put our code and the 
second one we will call it singleton  inside his constrctor  we will throw an error with the right way to get and instantiate  the object. after u use the right method from the error massage we will put an if statment 
if there is no object it will create one but if there are a object it will return it [Read more!](https://medium.com/swlh/node-js-and-singleton-pattern-7b08d11c726a). 


### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
dont be duplicated 


* Router Middleware
Router is one of those middleware, what it does actualy is to take the original request, and forward it to a sub handler according to the path example : "/home" for a GET request is mapped to function getHome that handle it and eventually send a response to the client on the behalf of the original handler.

* Dynamic Module Loading
  a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.

* Singleton Pattern
  ingleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance.
  
* CRUD -> REST Method Matches
  Create, Read, Update, Delete
* Mock Testing
  Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.