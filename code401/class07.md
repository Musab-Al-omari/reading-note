# Reading: Bearer Authorization

### Write the following steps in the correct order:
1. Register your application to get a client_id and client_secret
2. Ask the client if they want to sign in via a third party
3. Make a request to a third-party API endpoint
4. Make a request to the access token endpoint
5. Receive access token
6. Redirect to a third party authentication endpoint
7. Receive authorization code


### What can you do with an authorization code?




### What can you do with an access token?
Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user's data. Access tokens must be kept confidential in transit and in storage


### What’s a benefit of using OAuth instead of your own basic authentication?

in the  basic authentication u have to send ur login every time and ur information will be saved in the server 






* Client ID :
The client_id is a public identifier for apps returns the universally unique identifier of the Client object.

* Client Secret:
* 
A client secret is a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors. Protect your client secrets and never include them in mobile or browser-based apps.

* Authentication Endpoint :
  
Endpoint authentication is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service. ... The password response sent from the registered device verifies that the user is connecting from an authorized endpoint.connecting device.

 * Access Token Endpoint :
  The token endpoint is where apps make a request to get an access token for a user which is a key that allows you to enter protected resources.
 
 * API Endpoint :
An API endpoint is a point at which an application program interface (API) -- the code that allows two software programs to communicate with each other -- connects with the software program. APIs work by sending requests for information from a web application or web server and receiving a response.

 
 * Authorization Code :
  
An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.
 
 * Access Token:
Access tokens are used in token-based authentication to allow an application to access an API.












### What is JSON Web Token?
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. [Read more!](https://jwt.io/introduction/). 
