# Class 33 Notes Authentication and Production Server

## Why is this important?

- JWT's are important for validating the integrity of a JSON's contents as well as ensuring a message is seen on a need to know basis.

- Since the built-in runserver can't handle production environments, alternate options are needed, like Docker and Gunicorn.

## Reading Questions

1. JSON Web Tokens (JWTs) securely transmit information in a JSON object format.  When you would use JWTS: Authorization and Information Exchange.  JWTs have a header, payload and signature that are all encrypted before being sent and decrypted when received.  

2. In order to implement them together you must create a custom backend that validates the JWTs' contents.  From there you can set the `DEFAULT_AUTHENTICATION_CLASSES` to use your custom JWT backend.

3. Django's built-in runserver is not suitable for production environments because of it's lack of scalability and security concerns.  Some alternate server options for deploying a Django app are Docker and Gunicorn.

## Things I want to know more about

- N/A