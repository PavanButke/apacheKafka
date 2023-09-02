## What's Kafka?
1. Platform includes Kafka Cluster
2. Kafka cluster is like PubSub ; which publishes events and you can consume them various apis
3. Can consist of low level apis which consist of producer and consumer apis
4. a connect api to connect with third party system
5. creates topics and partitions
6. topics are collection of same items
7. partitions is distrubuted to diffrent machines
8. topics are set of partitions

![Kafka](image-3.png)

-kafka has leader based architecture


## Kafka at High Level Arch
![High Level Arch](image.png)
-zookeper
![with zookeper](image-1.png)
-kraft controllers
![with kraft](image-2.png)
