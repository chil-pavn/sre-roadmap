# Synchronous
In synchronous communication the caller waits for the response to arrive within some expected timespan. Typical examples would be HTTP based protocols like REST or GraphQL. The request-response model forces the client to handle errors immediately and implement countermeasure techniques (like retries) to become available and operational. This kind of inter-service communication often makes for tightly coupled systems but they are easy to implement and well understood.

# Asynchronous
In asynchronous communication between systems, the caller sends a message and continues with its other tasks not waiting for the answer. When the response eventually arrives it handles it as any other arriving message. It is in contrast with synchronous communication where the caller waits for the answer. The asynchronous communication could be realized using an asynchronous framework like Akka Cluster, or by using some external component like Kafka, Pulsar or RabbitMQ.

| Synchronous | Asynchronous |
| -------- | -------- |
| Intuitive, Synchronous systems are well understood and easy to implement. You either get an answer in a timely manner or you need to handle an error, which is easy to reason about. | Loosely coupled, Consumers and producers are by definition decoupled. The message broker sitting between the services makes it possible for the services to not know about each other while handling all the routing and persistence of messages. |
| No additional complexity, Synchronous communication doesn't require additional components (like message brokers) to handle communication, so there is no extra complexity of deploying and operating additional components..| Resilient, Decoupled services work independently and failure in one doesn’t cause a failure in another. The client of the service won’t be immediately affected. This makes it easier to achieve high-availability of mission-critical systems. |
|        | Easily scalable, Asynchronous services tend to consume less resources and components in microservices architecture tend to do one thing only. These facts combined with sharding at the message broker level make asynchronous messaging integrations the most viable option for scaling. |

References:

[GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-synchronous-and-asynchronous-transmission/)

[javatpoint](https://www.javatpoint.com/synchronous-vs-asynchronous-transmission)

