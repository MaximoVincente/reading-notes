# "Class 12" Reading Notes 📖

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
   - 100’s = These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
   - 200’s = These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.
   - 300’s =These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.
   - 400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc.
   - 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.
2. What is a status code 202?
   - Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.
3. What is a status code 308?
   - Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.
4. What code would you use if an update didn’t return data to a client?
   - Code 204
5. What code would you use if a resource used to exist but no longer does?
   - Code 410
6. What is the ‘Forbidden’ status code?
   - 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
   - When we deploy our application, we want use something that is not are local host, so we need to pull our into an environment variable.
2. What is middleware?
   - Code that runs when the server gets the request but before it gets passed to the routes.
3. What does app.use(express.json()) do?
   - Lets our server accept JSON as a body instead of a POSTelement or get element.
4. What does the /:id mean in a route?
   - It means that it is a parameter that we can access.
5. What is the difference between PUT and PATCH?
   - PATCH only updates based on what the user passes us. PUT Would update all the information
6. How do you make a default value in a schema?
   - default:
7. What does a 500 error status code mean?
   - It means that there's an error on the server.
8. What is the difference between a status 200 and a status 201?
   - 200: Everything was succesful, and 201: is more specific

## Things I want to know more about

## References

- [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
- [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
