# Reading Class 12 CRUD

## Why is this important

- Understanding status codes are important to debug and isolate the problem.

- MongoDB is a tool developers can use to integrate non relational databases into their applications for storage.

## Status Codes Based On Rest Methods

- 100s: Heads up

- 200s: It worked!

- 300: Wrong way! The thing you want isn't here

- 400: User issue!

- 500: Server issue!

1. "Code tells the client that the request valid, but its processing will finish sometime in the future" [source](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

2. Client needs to use another URL to find what they're looking for because it's not at this address anymore.

3. 204 No content

4. 410 Gone

5. 403 Forbidden

## Build A REST API with Node.js, Express, & MongoDB

1. It has your password that allows you to access your collection

2. Code that is run when the server gets a request but before it gets passed to the route

3. Allows us to use any middleware that we might need

4. It's the endpoint of the route.

5. Put= Update or create something at a URL.  Patch = Partially update the resource at a given url.

6.  `const Schema = mongoose.Schema;`?

7. The server encountered a problem that is preventing it from fulfilling the request.

8. 200 means that the request was successful while 201 also indicates that the request was succesful but it also made a new resource

## Questions

- N/A
