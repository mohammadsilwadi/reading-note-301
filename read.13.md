# [reading-note-301](https://mohammadsilwadi.github.io/reading-note-301/)
###  describe what each group of status code represents:

+ 100’s = Informational responses
+ 200’s = Successful responses
+ 300’s = Redirects 
+ 400’s = Client errors 
+ 500’s = Server errors 

### What is a status code 202?
202 Accepted

    The request has been received but not yet acted upon. It is noncommittal, since there is no way in HTTP to later send an asynchronous response indicating the outcome of the request. It is intended for cases where another process or server handles the request, or for batch processing.
### What is a status code 308?
308 Permanent Redirect

    This means that the resource is now permanently located at another URI, specified by the Location: HTTP Response header. This has the same semantics as the 301 Moved Permanently HTTP response code, with the exception that the user agent must not change the HTTP method used: If a POST was used in the first request, a POST must be used in the second request.
### What code would you use if an update didn’t return data to a client?
404 

### What code would you use if a resource used to exist but no longer does?

204  

### What is the ‘Forbidden’ status code?
403 

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

 to protect our information.

 ### What is middleware?

 Middleware is software which lies between an operating system and the applications running on it.

 ### What does app.use(express.json()) do?
 sending data (in the form of some data object) 
 ### What does the /:id mean in a route?
 it is a parameter.
 ### What is the difference beween PUT and PATCH?
 PUT method uses the request URI (replace an existing resource ) and PATCH method supplies a set of instructions to modify the resource(update an existing resource ).

 ### How do you make a defalut value in a schema?

 Make mongoose string schema type default value as blank and make the field optional. testschema = mongoose. Schema({ name:{ type:String, required:true, unique:true },
 ### What does a 500 error status code mean?
Internal Server Error server error response
### What is the difference between a status 200 and a status 201?
The 200 status code >> the request was received and understood and is being processed.
A 201 status code>>>that a request was successful and as a result, a resource has been created.
 

