Navi
=========
Navi is a distributed service framework that provides cluster management and high performance RPC. With Navi, you can easily build distributed applications with minimal effort to create a highly scalable architecture capable of handling remote procedure call and service registration and discovery.

Implemented in Java, Navi wraps ZooKeeper and uses Protostuff/Protobuf for transport to make it easy to build a cluster aware application. Navi allows you to focus your efforts on your application logic, so programming experience is very friendly with its simple XML or annotation configuration.

### Navi features include:
    Providing group management. Norbert uses zookeeper for the underlying group management, thus makes it easy to add or remove service nodes or to change configurations in the cluster.
    Using optional software load balancing and failover strategy .
    Providing Protostuff/protobuf to serialize and deserialize data
    Simple configuration with XML or annotation way to expose services.
