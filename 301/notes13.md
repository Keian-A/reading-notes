# Read-13

## Notes on [status codes based on REST methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:
  - 100’s = These error codes deal with information, for example if something goes wrong with the header somewhere on its journey to the server.
  - 200’s = These are success codes, which tells the client that their request has been accepted, but not neccessarily processed.
  - 300’s = These are redirection codes, which tells the client the information they seek isn't at the path they asked it for anymore.
  - 400’s = These are client error codes, which tell the client some of the information they are sending isn't correct. These can cause "timeouts, wrong URI, missing authentication, etc." (quotes directly from link)
  - 500’s = These are server error codes, these can be because either the servers are full, but also be an issue with information requested, the best course is to resend an identical request if this is received.
2. What is a status code 202?
  - This tells the client that the request was valid, but it will be processed sometime in the future.
3. What is a status code 308?
  - This tells the client another URL path to get the resource, since the one used in the request isn't in use anymore.
4. What code would you use if an update didn’t return data to a client?
  - 204 No Content
5. What code would you use if a resource used to exist but no longer does?
  - 307 Temporary Redirect
6. What is the ‘Forbidden’ status code?
  - The client has or has no need to authorize yet still has no permissions to access the desired response data.

## Notes on [Build a REST API with Node.js, Express, & MongoDB](https://www.youtube.com/watch?v=fgTGADljAeg&t=8s)

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - Since we will be using a third party site to host the database on the live site, we will not be able to use localhost for the live deployment.
2. What is middleware?
  - Middleware is the middle man between the server and other applications or databases.
3. What does app.use(express.json()) do?
  - This allows the server to accept json data files.
4. What does the /:id mean in a route?
  - This will allow the server to get whatever data is passed in the route as a parameter. The colon in front of it makes it a parameter. `req.params.id`
5. What is the difference beween PUT and PATCH?
  - PATCH only updated based on what the user passes you, I.E. if the user only passes you a name, you only want to update the name of the object. PUT updates all information in the object at once.
6. How do you make a default value in a schema?
  - with the `default` key separated with the default value with a colon.
7. What does a 500 error status code mean?
  - This means there is an error on the server.
8. What is the difference between a status 200 and a status 201?
  - 201 means successfully created object (more specific), 200 means everything was successful.

[<-- Back](ToC.md)