# Question
1. What is AMQP?
AMQP (Advanced Message Queuing Protocol) is an open standard for message-oriented middleware. It enables different applications to communicate and exchange data in a reliable, efficient, and structured way. AMQP is widely used in distributed systems, particularly in scenarios where high reliability and seamless interoperability are critical, such as microservices architectures.

2. What does guest:guest@localhost:5672 mean?
This is a common default connection string for RabbitMQ.
- The first guest represents the username
- The second guest is the password
- localhost:5672 specifies that RabbitMQ is running on the local machine (localhost) and listening on port 5672 (the default AMQP port)awjd