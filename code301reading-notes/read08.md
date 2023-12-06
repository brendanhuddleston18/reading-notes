# Readings Class 08 APIs

## Why is this important?

- APIs are important because they allow devs to utilize data from somewhere else on their application.

## API Design Best Practices

1. REST stands for Representational State Transfer

2. "REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client" [source](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

3. A URI uniquely identifies a resource. `https://adventure-works.com/orders/1` would be an example of a URI

4. The most common HTTP verbs are `GET`, `POST`, `PUT`, `PATCH`, and `DELETE`

5. "URIs should be based on nouns(the resource) and not verbs (the operations on the resource)" [source](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

6. `https://brendan-store.com/shopping-list`

7. "Chatty web APIs are those that expose a large number of smaller resources" [source](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design) They are not a good thing. 

8. A successful `GET` returns `HTTP status code 200`

9. An unsuccessful `GET` returns `404(Not Found)`

10. A successful `POST` can return `Status Code 200`(Does not create a new service), `Status Code 201`(Creates a new resource), `Status Code 204`(No result to return)

11. A successful `delete` request returns `Status code 204`(No content)

## Things I want to know

- No questions yet