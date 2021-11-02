# Express REST API

## Name 3 real world use cases where youâ€™d want to change the request with custom middleware:
* Auth middleware
* Robot Middleware
* Logging Middleware

## True or false: The route handler is middleware?
* true.

## In what ways can a middleware function end the process and send data to the browser?
* Sending an error message by passing a string to next("string")

## At what point in the request lifecycle can you “inject” middleware?

* Between in the middle of the request and the response .

## What can cause express to error with “Request headers sent twice, cannot start a second response”

* When a server tries to send several responses for one request

---

### Middleware

* Middleware is software which lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications. It is sometimes called plumbing, as it connects two applications together so data and databases can be easily passed between the “pipe.” Using middleware allows users to perform such requests as submitting forms on a web browser or allowing the web server to return dynamic web pages based on a user’s profile.

### Request Object
* The req object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on.

### Response Object

* The response object is an instance of a javax. servlet. http. HttpServletResponse object. Just as the server creates the request object, it also creates an object to represent the response to the client

### Application Middleware

* ommon middleware examples include database middleware, application server middleware, message-oriented middleware, web middleware and transaction-processing monitors. ... This can include security authentication, transaction management, message queues, applications servers, web servers and directories

### Routing Middleware
* Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware
