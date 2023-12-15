# Reading 15 Reading

## Why is this important

- OAuth is important for single sign on API access and for authentication of users.

- Authorization/Authentication are important things to implement in order to keep user information secure as well as application information.

## What is OAuth 

1. OAuth(Open-standard Authorization Protocol) describes how unrelated servers and services can safely allow authenticated acces to their assets without actually sharing the initial, related, single logon credential.

2. An example would be when you're trying to sign in to netlify and you can sign in with GitHub.

3. OpenID is a single sign in protocol where users would create a single account to sign into multiple sites.

## Authorization and Authentication flows

1. Authentication verifies the identity of whoever is signing in while authorization determines what the user has the permission to do.

2. Authorization code flow is: "Exchanging an authorization code for a token" [source](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

3. Authorization Code Flow with proof key for code exchange(PKCE) is mitigation of additional security by providing the user with a PKCE.

4. Implicit Flow with Form Post is intended for public clients or apps. which are unable to securely store Client Secrets.  It offers a streamlined workflow if the app. needs only an ID token to perform user auth. [source](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

5. Client Credentials Flow allows client to obtain an access token by presenting its client credentials to the server.

6. Device authorization flow is when a device redirects a user to a link to authorize.

7. Resource Owner Password Flow requests that users provide username and password. 

## Questions I have

- What is the difference between authorization code flow and authorization code flow with PKCE?