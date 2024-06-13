## Concepts
- Pubsub message architecture
    - Producer(Message producer)
    - Broker
    - Subscriber(Message consumer)

- Components
    - producer
    - consumer
    - broker
    - cluster: Group of computer each running one instance for common goal
    - topic: Dataset table
    - partitions: partition of each topic
    - partition offset: unique sequence id of every message
    - consumer group: Share workload

- When to Use:
    - Data integration patterns
    - Microservices architecture for stram processing
    - Real time streaming in data warehouse and Data lake

    - Examples:
        - Custom In House Appln: Kafka client api, embeded kafka consumer and producer
        - COTS Product: Kafka connect
        - Real time stream application: Kafka broker, client api(producer), Kafka stream
        - Ream time stream in data warehouse/datalake - Kafka broker(cluster)
