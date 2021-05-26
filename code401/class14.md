# Readings: Event Driven Architecture



#### What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.
#### How can the server be assured a message was properly received?
by reserving the message in the waiting queue so when ever the user connect it will be sent auto
#### What classic design pattern is best represented by event driven programming?
no idea Xd

#### How do you test an event driven system?
by building a website base on it 



#### FIFO ;-Queue FIFO (First-In-First-Out) queues are designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated.

#### Pub/Sub Pub/Sub is an asynchronous messaging service that decouples services that produce events from services that process events.