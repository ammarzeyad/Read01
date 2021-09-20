# What does REST stand for?

- an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

## REST APIs are designed around a ____?

- an order resource might be implemented internally as several tables in a relational database, but presented to the client as a single entity. Avoid creating APIs that simply mirror the internal structure of a database. The purpose of REST is to model entities and the operations that an application can perform on those entities. A client should not be exposed to the internal implementation.

## What is an identifer of a resource? Give an example?

- GET retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

## What are the most common HTTP verbs?

- GET methods
A successful GET method typically returns HTTP status code 200 (OK). If the resource cannot be found, the method should return 404 (Not Found).

- POST methods
If a POST method creates a new resource, it returns HTTP status code 201 (Created). The URI of the new resource is included in the Location header of the response. The response body contains a representation of the resource.

## What should the URIs be based on?

- resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

## Give an example of a good URI?

- <https://adventure-works.com/orders> // Good

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- Another factor is that all web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires and it bad.

## What status code does a successful GET request return?

- GET retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

## What status code does an unsuccessful GET request return?

- If not valid, 400 Bad Request is returned.

## What status code does a successful POST request return?

- POST creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.

## What status code does a successful DELETE request return?

- DELETE removes the resource at the specified URI.
