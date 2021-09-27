# In your own words, describe what each group of status code represents?

- 100's = These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.

- 200's = These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

- 300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

- 400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

- 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

## What is a status code 202?

- The request has been accepted for processing, but the processing has not been completed.

## What is a status code 308?

- The resource requested has been definitively moved to the URL given by the Location headers.

## What code would you use if an update didn’t return data to a client?

- 204 No Content.

## What code would you use if a resource used to exist but no longer does?

- 410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.

## What is the ‘Forbidden’ status code?

- 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- For security concerns, we don't want to push our MongoDB database string.

## What is middleware?

- Middleware is a type of computer software that provides services to software applications beyond those available from the operating system.

## What does app.use(express.json()) do?

- express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.

## What does the /:id mean in a route?

- URL segments, also known as route parameters, are used to record the data given at their location in the URL. The captured values are stored in the req.params object as keys, with the name of the route parameter provided in the path as the value.

## What is the difference beween PUT and PATCH?

- PUT is a method of modifying resource where the client sends data that updates the entire resource. PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

## How do you make a defalut value in a schema?

- Using the default setting: Default values for specific routes can be defined in your schemas. If you don't specify a path when you create a new document, the default will be used.
