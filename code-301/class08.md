## APIs

### [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

#### What does REST stand for?

> Representational State Transfer (REST) is an architectural approach to designing web services

#### REST APIs are designed around a ____.

> REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

#### What is an identifier of a resource? Give an example.

> An identifier of a resource is a unique reference that allows the client to locate and interact with a specific resource, typically represented by a URL.
Example: `https://example.com/api/posts/123`


#### What are the most common HTTP verbs?

> GET, POST, PUT, DELETE, PATCH, HEAD, and OPTIONS.

#### What should the URIs be based on?

> (Uniform Resource Identifiers) in RESTful architecture should be based on the resources themselves. The URIs should represent the resources that the API exposes and provide a unique and meaningful identifier for each resource.

#### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

> Having a "chatty" web API refers to an API that requires a high number of small, fine-grained requests to accomplish a specific task or retrieve data. In other words, it means that the API design necessitates multiple round-trips between the client and the server to perform a single operation, and is typically considered a bad thing.

#### What status code does a successful GET request return?

> This typically returns a status code of 200 OK.

#### What status code does an unsuccessful GET request return?

> An unsuccessful GET request can return various status codes depending on the specific reason for the failure.

1. 404 Not Found: indicates that the requested resource was not found on the server.

2. 403 Forbidden:  indicates that the server understood the request, but the client does not have the necessary permissions to access the requested resource. 

3. 401 Unauthorized: indicates that the requested resource requires authentication, and the client must provide valid credentials to access it. It signifies that the client needs to authenticate before accessing the resource.

4. 400 Bad Request: indicates that the server cannot process the request due to a client error.

5. 500 Internal Server Error: This status code indicates an internal server error.

#### What status code does a successful POST request return?

> This typically returns a status code of 201 Created or 200 OK, depending on the specific scenario.

#### What status code does a successful DELETE request return?

> This typically returns a status code of 204 No Content or 200 OK.

*Bookmarked and Reviewed*

- [RegExr](https://regexr.com/)

- [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

- [Regex 101](https://regex101.com/)
