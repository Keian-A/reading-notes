# Read-13

## Responses to Read-13 questions

1. What does it mean that web sockets are bidirectional? Why is this useful?
  - This means that information is sent both directions. This is useful for what can be thought of as a request / response dataflow.
2. Does socket.io use HTTP? Why?
  - Yes, socket.io was constructed so that HTTP and websocket servers can co-exist on the same port.
3. What happens when a client emits an event?
  - A like-subscription on the server picks up on this.
4. What happens when a server emits an event?
  - A like-subscription on the client picks up on this.
5. What happens if a client “misses” an event?
  - Packets are dropped, causing data loss.
6. How can we mitigate this?
  - You can decide to drop sockets if they are older than specified.

Define:
- Socket
  - An instance of a client connected to a server.
- Web Socket
  - This is a computer communications protocol. AKA a way a computer has of communicating information between multiple servers & clients.
- Socket.io
  - Real-time bidirectional and event-based communication for sending multiple events accross multiple servers & clients.
- Client
  - This is one application that is connected to one or multiple servers.
- Server
  - These are the data/information-centers that connect multiple clients to eachother or deal with responding to a request.
- OSI Model
  - This is the 7 layer model of explaining the functions of a networking system.
- TCP Model
  - This is a more concise version of the OSI model, consisting of only 4 layers.
- TCP
  - Transmission Control Protocol - The transport protocol that is used [on top of IP to ensure reliable transmision of packets](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:transporting-packets/a/transmission-control-protocol--tcp#:~:text=The%20Transmission%20Control%20Protocol%20(TCP,duplicate%20packets%2C%20and%20corrupted%20packets.)
- UDP
  - User Diagram Protocol - The communications protocol that is used for [establishing low-latency and loss-tolerating connections between applications on the internet.](https://searchnetworking.techtarget.com/definition/UDP-User-Datagram-Protocol#:~:text=UDP%20(User%20Datagram%20Protocol)%20is,provided%20by%20the%20receiving%20party.)
- Packets
  - These are the raw data send between connections that the headers tells to reconstruct properly into the data.

1. Which 3 things had you heard about previously and now have better clarity on?
  1. packets
  2. TCP
  3. UDP
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  1. OSI model
  2. socket.io
  3. socket
3. What are you most excited about trying to implement or see how it works?
  - Socket.io

[<-- Back](ToC.md)