# Event Driven Architecture

### What’s the difference between a FIFO and a standard queue?
* FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.

### How can the server be assured a message was properly received?
* the receiver send a notification to the server that the message is received and emit a function to delete the message from the queue.

### What classic design pattern is best represented by event driven programming?
* The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

### How do you test an event driven system?
* tests for the functions or by emitting events

### terms
* FIFO Queue - First In First Out Queue
* Pub/Sub - async messaging that separates event creation from event processing

---

### Preview

#### Which 3 things had you heard about previously and now have better clarity on?
* Socket ,
authentication & authorization ,
ACL.

#### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
* Aws ,
Socket.io ,
OSI Model.

#### What are you most excited about trying to implement or see how it works?
* AWS
