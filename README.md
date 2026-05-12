# a. What is amqp?

AMQP (Advanced Message Queuing Protocol) is an open standard protocol for message-oriented middleware. It lets applications send, receive, and route messages reliably through a message broker.

# b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what
is the second guest, and what is localhost:5672 is for?

guest:guest@localhost:5672 is the connection URI for the RabbitMQ broker:
- First guest:username.
- Second guest:password.
- localhost:5672: the broker's host and port; 5672 is the default AMQP port.