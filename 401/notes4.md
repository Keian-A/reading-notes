# Read-04

## Notes on review of express-type routing

1. Name 3 real world use cases where you’d want to change the request with custom middleware
  - Password checking before sending the client information on their account
  - Sensitive information being collected
  - Verification of available information on records
2. True or false: The route handler is middleware?
  - false
3. In what ways can a middleware function end the process and send data to the browser?
  - Middleware can test something, and have an `if` statement check if data is there or not, if it is it could `next()` to the next available route, or `res.status(404)` from invalid information given
4. At what point in the request lifecycle can you “inject” middleware?
  - As soon as the request gets to the server, the server's event loop gets into the middleware first before reaching the appropriate route.
5. What can cause express to error with “Request headers sent twice, cannot start a second response”
  - Somehow the server sent two responses back to the client, which most likely means a `next()` was after a `res.send` or `res.json`

## Define:

- Middleware: These are functions / routes that achieve a specific goal, before sending the event loop on the server to the next available route.
- Request Object: This is the object sent to the server for route handling.
- Response Object: This is the object the server sends back the client after finished with handling the request.
- Application Middleware: This is the type of middleware that lives on application-level routing, which covers every request sent to the server.
- Routing Middleware: These are routes that include the next() function, which their sole purpose is to achieve something on specific request types (similar to how classes work in html / css that you can have multiple things with the same class attribute and the change cascades for all elements with the specified class attribute).
- Test Driven Development: The method of writing code that involves writing tests for each "function" of the code, so there are checks in place to see if / where something fails.
- Behavioral Testing: This is testing of the `external behavior` of the program AKA [black box testing](https://www.tutorialspoint.com/software_testing_dictionary/behaviour_testing.htm#:~:text=Behavioural%20Testing%20is%20a%20testing,is%20usually%20a%20functional%20testing.)

[<-- Back](ToC.md)