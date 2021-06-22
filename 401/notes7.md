# Read-07

## Notes on Bearer Authorization

1. Write the following steps in the correct order:
  - Register your application to get a client_id and client_secret
  - Ask the client if they want to sign in via a third party
  - Make a request to a third-party API endpoint
  - Receive access token
  - Receive authorization code
  - Make a request to the access token endpoint
  - Redirect to a third party authentication endpoint
2. What can you do with an authorization code?
  - The client can exchange this for an access token to view a website.
3. What can you do with an access token?
  - Allows users to navigate a security-protected space.
4. What’s a benefit of using OAuth instead of your own basic authentication?
  - OAuth provides a universally acceptable access token, so you can have one account for a plethora of different websites. (or use your email)

### Define:
- Client ID
  - This represents each unique browser / device that is using the website.
- Client Secret
  - This is [a secret known only to your application and the authorization server](https://auth0.com/docs/applications). This only grants tokens to "authorized requestors".
- Authentication Endpoint
  - This is the process that ensures only authorized users can have access to a specific application.
- Access Token Endpoint
  - This is where the app makes a request for the tokens.
- API Endpoint
  - This is one end of a connection between an API and something interacting with it.
- Authorization Code
  - This is an alphanumeric password that allows the user to enter information in a security-protected space.
- Acess Token
  - This is the token-based authentication that allows a user to interact with an API.