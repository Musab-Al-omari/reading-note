# Readings: Express

### first question
#### What’s the difference between PUT and PATCH?
##### PUT 
overwrites the entire entity if it already exists, and creates a new resource if it doesn’t exist.


##### PATCH 
applies a partial update to the resource. 



### second question
#### Provide links to 3 services or tools that allow you to “mock” an API for development like `json-server`
##### Mocky
Mocky is an incredibly simple and super lightweight testing implementation. Mocky is entirely a web app, meaning that everything is generated and managed remotely. This does mean that Mocky grants you significantly less control compared to solutions that focus more on local systems, but this also means the application is simpler and cleaner.

Mocky has great support for a ton of common functionality, but because it is a web app, you have to add this functionality in URL form. For instance, adding ?callback=myfunction enables jsonp; adding ?mocky-delay=100ms allows you to add delays. This sort of functionality still delivers quite a lot of value, but it does point to the relative simplicity of the app – if exceeding granular control is something that is desired, Mocky might not be the first option. For simple interactions, however, Mocky is a great choice.

#### Postman Mock Server
Mock Servers in Postman are tied directly to the Postman app, and for that reason, are a suggestion for a very particular use case. Postman is a great testing solution, and their mocking system is equally great, but the fact that it’s tied to both a Postman account and a defined collection means that using only the Mocking system means that you are buying into an incomplete testing experience. You can create a mock server without an existing collection, but in this case it’s kind of like buying an entire sewing kit for a single needle.

That may not be a deal-breaker, of course – Postman is an excellent testing system and is in relatively common use by many API developers. Still, the fact that the mocking system is but a single aspect of a much larger testing apparatus may deter some users. There’s also the fact that it’s not completely free – Postman allows a limited number of free mock calls, but users engaging in heavy development may quickly find themselves exhausting this limited number.



#### Mockserver
Mockserver is a library that utilizes mock files in order to serve realistic mock responses. It does this by creating local mock files that serve content as if they were part of a real API localized on port 9001. Because of the relatively clean and quick implementation, Mockserver boasts that API mocking can be created in “a matter of seconds” – more to the point, because such a system is super lightweight, it also means that it’s highly adaptable across a wide range of options.

For this reason, Mockserver is a great option if quick testing is needed with relative immediacy. Mockserver is verbose, supports custom headers, has a built-in response delay simulation scheme, and offers a wide range of additional options to mimic standard testing environments.


### third question
#### Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
Popularity: By comparing stats,  swagger-ui is more popular then apidocjs.
Consistency: If we already using swagger for our Dotnetcore service, then implementing swagger tool will consist more from Info and UI prospective.
Implementation complexity: apidocjs and swagger both required documentation content on implemented method as customize comment data. In addition they allow to write documentation data in separate resource file as .js and .json. If we already have swagger.json created by DotnetCore we can reuse more than 80% specification.
 Maintenance: For apidocjs will have to modify documentation for each affected method/endpoints if service changed. In swagger we can limit changes. But by implementing apidocjs we can isolate the layer.
Other benefits: Because swagger use plain .json that could be parsed through programing language, thus we can get advantage of various other 3rd parties in order to create http client and more. 
Future: Due to popularity of swagger, apidocjs provide information about apidoc-swagger converter so we can switch apidoc to swagger anytime.

### swagger
`
responses:
        200:
          description: OK
        400:
          description: Bad request. User ID must be an integer and bigger than 0.
        401:
          description: Authorization information is missing or invalid.
        404:
          description: A user with the specified ID was not found.
`
### APIDoc.js

`
responses:
        200:
          description: OK
        400:
          description: Bad request. User ID must be an integer and bigger than 0.
        401:
          {
            "isError": true,
            "errorCode": 401, //--- or 500 depends on error type
            "errorMessage": "Not authorized"
            }
        404:
          description: A user with the specified ID was not found.
`










