## CRUD

### [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

#### In your own words, describe what each group of status code represents:

> 100’s = known as informational responses. These codes are used to acknowledge that a request has been received and understood.

> 200’s = successful responses. These codes indicate that the client's request was successfully processed by the server

> 300’s = redirection. These codes are used when a resource has moved or is temporarily available at a different location. 

> 400’s = client errors. These codes indicate that there was an issue with the client's request. They are often caused by errors in the request syntax, missing or invalid parameters, or authentication problems

> 500’s = server errors. These codes indicate that there was an issue on the server side while processing the request. They typically occur when the server encounters an unexpected condition or fails to fulfill the request.

#### What is a status code 202?

> Accepted. An HTTP response status code that indicates that the request has been accepted for processing but has not yet been completed.

#### What is a status code 308?

> Permanent Redirect. An HTTP response status code that indicates that the requested resource has been permanently moved to a new location.

#### What code would you use if an update didn’t return data to a client?

> The appropriate HTTP status code to use would be 204 No Content. This code indicates that the server has successfully processed the request and does not need to return any content in the response body.

#### What code would you use if a resource used to exist but no longer does?

> The appropriate HTTP status code to use would be 410 Gone. This status code indicates that the requested resource is no longer available and has been intentionally removed.

#### What is the ‘Forbidden’ status code?

> Represented by the code 403. It indicates that the server understood the request made by the client, but it refuses to fulfill it or provide access to the requested resource.

### [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

> Storing sensitive information, such as database connection strings, in server code can expose them to potential security risks. If the server code is compromised or shared publicly, the sensitive information becomes easily accessible. 

#### What is middleware?

> This refers to a software component or a set of functions that sit between the client and the server, intercepting and processing incoming requests and outgoing responses.

#### What does app.use(express.json()) do?

> This function is used to add middleware that parses incoming requests with JSON payloads. It specifically enables the server to handle and interpret JSON data sent in the request body.

#### What does the /:id mean in a route?

> This is used as a parameter placeholder, where "id" represents a variable value that can be extracted from the URL. It allows you to define dynamic routes that can handle different values for the specified parameter.

#### What is the difference between PUT and PATCH?

> The key distinction is that PUT is used for complete replacement of a resource or creation of a new resource, while PATCH is used for partial modifications or updates to an existing resource. PUT requires sending the complete representation of the resource, whereas PATCH only sends the changes or updates that need to be applied.

#### How do you make a default value in a schema?

> To set a default value in a schema, you can use the default property when defining the schema in a framework like Mongoose, which is commonly used with MongoDB.

#### What does a 500 error status code mean?

> A"500 Internal Server Error," is an HTTP status code that indicates a generic server-side error has occurred. It is a response from the server to indicate that it encountered an unexpected condition or encountered an error that prevented it from fulfilling the request.

#### What is the difference between a status 200 and a status 201?

> The 200 status code signifies a successful request with the requested resource or operation result in the response. The 201 status code specifically indicates the successful creation of a new resource, with the response including the URI of the newly created resource.

## Things I want to know more about
