# Read-08

## Notes on Access Control

1. When is Basic Authorization used vs. Bearer Authorization?
  - Basic-Authorization is used when the user needs to recieve a server-verified token to use in any more advanced requests. Once this token is used, THEN bearer-authorization is used for the *advanced* requests to the server using the token.
2. What does the JSON Web Token package do?
  - JWT allows the server to create a token specific to the 'SECRET' variable specific to the server, in turn, allowing only approved users to access approved data or information.
3. What considerations should we make when creating and storing a SECRET?
  - The 'SECRET' needs to be specific to the server, and so no one else can either brute force, or re-create their own token-generation system for your server. This needs to be random, and unique.

## Define:
- encryption
  - This is the process of **hiding** data in a way that can't be used to recover the original data, only compared with something to see if they match.
- token
  - This is a server / API specific string that is used to access data that requires one (a token).
- bearer
  - This is the naming convention to indicate that the incoming data from the client should be used for bearer-authentication (requiring of a token).
- secret
  - JWT uses this to generate a token using both the secret *and* data it wraps up using this. This should be server specific and completely random as to not have anyone else brute force their way into your server.
- JSON Web Token
  - JWT is a service that is used to create and test tokens.

[<-- Back](ToC.md)