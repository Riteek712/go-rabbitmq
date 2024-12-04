# RabbitMQ Go Project

A simple Go project demonstrating the use of RabbitMQ for message queuing. This project includes functionality to send and receive messages using RabbitMQ.

## What is RabbitMQ?

RabbitMQ is a widely-used open-source message broker that facilitates communication between applications through message queues. It implements the Advanced Message Queuing Protocol (AMQP) and supports multiple messaging patterns such as:

- **Publish/Subscribe**: Send messages to multiple consumers.
- **Work Queues**: Distribute tasks among workers to balance loads.
- **Routing**: Direct messages to specific consumers based on routing keys.
- **Topics**: Deliver messages to multiple consumers based on patterns.

### Common Use Cases for RabbitMQ
- Decoupling services in microservices architectures.
- Task scheduling and background job processing.
- Real-time data streaming between systems.
- Logging and event-driven applications.

## How It Works in This Project

### Sending Messages
The **producer** sends messages to a RabbitMQ queue. The queue acts as a temporary storage for the messages until they are retrieved by a consumer.

### Receiving Messages
The **consumer** reads messages from the queue and processes them. This ensures reliable communication, as messages are stored until acknowledged by the consumer.

## Prerequisites
- Go installed (>=1.18)
- Docker installed

