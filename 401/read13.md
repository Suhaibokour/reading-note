# Message Queues

## What does it mean that web sockets are bidirectional? Why is this useful?
* BIDIRECTIONAL. Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time

## Does socket.io use HTTP? Why?
* Websocket is created when you make upgrade from http to websocket, so it kind of does need http. socket.io isn't a pure Websocket server/implementation, it depends on HTTP for its initial connection setup

## What happens when a client emits an event?
* the server listens for it and runs functions based on what’s attached to the listener

## What happens when a server emits an event?
* The event is sent to everyone

## What happens if a client “misses” an event?
* the messages will be ignored

### Term

* Socket: it was created to use open connections to facilitate realtime communication, still a relatively new phenomenon at the time.
* Web Socket: it is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server.
* Socket.io : it is a library that enables real-time, bidirectional and event-based communication between the browser and the server.
* Client: a computer hardware device or software that accesses a service made available by a server.
* Server: is a physical computer dedicated to run services to serve the needs of other computers. Depending on the service that is running, it could be a file server, database server, home media server, print server, or web server.
* OSI Model: The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.
* TCP Model: TCP model defines how devices should transmit data between them and enables communication over networks and large distances. The model represents how data is exchanged and organized over networks.
* TCP: TCP stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network.
* UDP: User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups.
* Packets: it is a small segment of a larger message.

