# Read-12

## Responses to Read-12 questions

1. What is the benefit of transforming data into packets?
  - Systems built on the use of packets are: ["cost-efective, efficient, and scalable networks for content delivery."](https://blog.fntsoftware.com/network-transformation-transitioning-to-packet-technology/#:~:text=TDM%2Dbased%20networks%20must%20transform,scalable%20networks%20for%20content%20delivery.)
2. UDP is often referred to as a connectionless protocol. Why is this?
  - It sends data often before the recieving party provides an agreement.
3. Can a socket server application have multiple socket connections?
  - Yes, the server can handle as many as resources will allow it to.
4. Can a socket connection application be connected to multiple socket servers?
  - Yes, this is restricted by the number of ports available to the connection application.
5. Can an application be both a socket server and a socket connection?
  - As long as the application and the server aren't using the same port at the same time, then yes.

Define:
- Term
  - A term in a definition of something to a smaller degree.
- Observer Pattern
  - A pattern where an object (the subject) maintains a list of its dependents (observers) and notifies them of any state changes.
- Listener
  - A line or place in code that "listens" or makes a change, when another piece of an application makes a change.
- Event Handler
  - What changes when an event being listened to makes a change.
- Event Driven Programming
  - This is the pattern in computer science that relys on changes in one part of code to change other parts either automatically or with a callback.
- Event Loop
  - This is the list of things a program runs through through execution.
- Event Queue
  - These are the events waiting to be processed.
- Call Stack
  - This is the code blocks (or functions) that are waiting to be processed.
- Emit/Raise/Trigger
  - Emit is used in socket-related programming to send a signal with to or from a server using a specific string that matches with one on the client.
- Subscribe
  - This is the "lingo" that is used when referring to the line of code that accepts a publication that us sent through `emit`.
- database
  - This is the place (usually a third party) that stores data for a plethora of applications to use.

- Which 3 things had you heard about previously and now have better clarity on?
  1. database
  2. event loop
  3. event handler
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  1. event queue
  2. emit & on
  3. event-driven programming
- What are you most excited about trying to implement or see how it works?
  - Emit / subscribe (essentially the whole socket.io implementation)

[<-- Back](ToC.md)