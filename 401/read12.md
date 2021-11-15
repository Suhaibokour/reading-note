# Socket.io

### What is the benefit of transforming data into packets?
* Packets are the basic units of communication over a TCP/IP network. Devices on a TCP/IP network divide data into small pieces, allowing the network to accommodate various bandwidths, to allow for multiple routes to a destination, and to retransmit the pieces of data which are interrupted or lost

### UDP is often refereed to as a connectionless protocol. Why is this?
* no connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted. As a result, the application must take care of data integrity all by itself

### Can a socket server application have multiple socket connections?
* A socket that has been established as a server can accept connection requests from multiple clients

### Can a socket connection application be connected to multiple socket servers?
* Yes - you need one socket for each connection. A socket is a client IP address + client port + server IP address + server port combination. If a client is talking to multiple servers, it is using multiple ports on the client machine

### Can an application be both a socket server and a socket connection?
* If you want to have a "peer-to-peer" type system, then you just have each client run both a client and a server socket - the server socket for accepting connections from other clients and the client socket for establishing connections to others

### Can an application be both a socket server and a socket connection?
* If you want to have a "peer-to-peer" type system, then you just have each client run both a client and a server socket - the server socket for accepting connections from other clients and the client socket for establishing connections to others


---
### 	Definitions
* Observer Pattern: The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
* Listener: An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.
* Event Handler: Event handling (overview) Events are signals fired inside the browser window that notify of changes in the browser or operating system environment. Programmers can create event handler code that will run when an event fires, allowing web pages to respond appropriately to change.
* Event Driven Programming: In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.
