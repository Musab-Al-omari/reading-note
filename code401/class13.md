# Readings: Message Queues


#### What does it mean that web sockets are bidirectional? Why is this useful?
This enables the server to send real-time updates after the  handshaking  without the need for the client to send requests

#### Does socket.io use HTTP? Why?
Socket.io, and WebSockets in general, require an http server for the initial upgrade handshake. So even if you don't supply Socket.io with an http server it will create one for you.
#### What happens when a client emits an event?
it send it for the server and the server call it  
#### What happens when a server emits an event?

#### What happens if a client “misses” an event?
no thing happen 
#### How can we mitigate this?



**Socket**
 A socket is one endpoint of a two-way communication link between two programs running on the network. 
**Web Socket**
is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection;
**Socket.io**
is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries.
**Client**
client is a computer or a program that, as part of its operation, relies on sending a request to another program or a computer hardware or software that accesses a service made available by a server (which may or may not be located on another computer).
**Server**
A server is a computer that serves information to other computers. 
**OSI Model**
(Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.
**TCP Model**
The TCP/IP model is a concise version of the OSI model.
**TCP**
The Transmission Control Protocol (TCP) is a transport protocol that is used on top of IP to ensure reliable transmission of packets
**UDP**
UDP (User Datagram Protocol) is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet.
**Packets**