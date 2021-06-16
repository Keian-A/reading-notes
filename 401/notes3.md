# Read-03

1. What’s the difference between `PUT` and `PATCH`?
  - `PUT` is a method that takes data from the request or from the serrver to replace the value saved.
  - `PATCH` is a method that takes data from the request or from the server to modify the value saved.
2. Provide links to 3 services or tools that allow you to “mock” an API for development like `json-server`
  - [Postman](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/)
  - [Stoplight](https://stoplight.io/mock-api-guide/basics/)
  - [Mockoon](https://mockoon.com/)
3. Compare and contrast Swagger and APIDoc.js 1. Which HTTP status codes should be sent with each type of (un)successful API call?
  - Swagger is open source
  - APIDoc.js [creates a documentation from API annotations in your source code](https://apidocjs.com/).
  - 100 Continue
  - 101 Switching Protocols
  - 103 Early Hints
  - 200 OK
  - 201 Created
  - 202 Accepted
  - 203 Non-Authoritative Information
  - 204 No Content
  - 205 Reset Content
  - 206 Partial Content
  - 300 Multiple Choices
  - 301 Moved Permanently
  - 302 Found
  - 303 See Other
  - 304 Not Modified
  - 307 Temporary Redirect
  - 308 Permanent Redirect
  - 400 Bad Request
  - 401 Unauthorized
  - 402 Payment Required
  - 403 Forbidden
  - 404 Not Found
  - 405 Method Not Allowed
  - 406 Not Acceptable
  - 407 Proxy Authentication Required
  - 408 Request Timeout
  - 409 Conflict
  - 410 Gone
  - 411 Length Required
  - 412 Precondition Failed
  - 413 Payload Too Large
  - 414 URI Too Long
  - 415 Unsupported Media Type
  - 416 Range Not Satisfiable
  - 417 Expectation Failed
  - 418 I'm a teapot
  - 422 Unprocessable Entity
  - 425 Too Early
  - 426 Upgrade Required
  - 428 Precondition Required
  - 429 Too Many Requests
  - 431 Request Header Fields Too Large
  - 451 Unavailable For Legal Reasons
  - 500 Internal Server Error
  - 501 Not Implemented
  - 502 Bad Gateway
  - 503 Service Unavailable
  - 504 Gateway Timeout
  - 505 HTTP Version Not Supported
  - 506 Variant Also Negotiates
  - 507 Insufficient Storage
  - 508 Loop Detected
  - 510 Not Extended
  - 511 Network Authentication Required
  - All taken from [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
4. Compare and contrast SOAP and ReST
  - SOAP
    - Simple Object Access Protocol
    - Is a protocol
    - Only works with XML formats
  - ReST
    - Representational State Transfer
    - Architectural pattern
    - Works with plain text, XML, HTML and JSON

Define:
- Web Server: Computer software that accepts HTTP requests and manipulates data in some form to send back to the client, or requests information itself from other servers.
- Express: A back-end web application framework for Node.js, designed for building web applications and APIs.
- Routing: Specific endpoints a request reaches or "hits" when it reaches a server, to ask for specific actions.
- WRRC: The Web Request Response Cycle is the process a client goes through when asking a server for data.

[<-- Back](ToC.md)