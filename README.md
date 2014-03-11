Navi
=========
Navi is a distributed service framework that provides cluster management and high performance RPC. With Navi, you can easily build distributed applications with minimal effort to create a highly scalable architecture capable of handling remote procedure call and service registration and discovery.

Implemented in Java and Spring framework, Navi wraps ZooKeeper and uses Protostuff/Protobuf for transport to make it easy to build a cluster aware application. Navi allows you to focus your efforts on your application logic, so programming experience is very friendly with its simple XML or annotation configuration.

## Features

*  Providing high availability. By using zookeeper for the underlying group management, Navi can make it easy to publish/remove service nodes.
*  Providing Protostuff/Protobuf to serialize and deserialize data.
*  Using optional software load balancing and failover strategy.
*  Simple configuration with XML or annotation way to expose services in Spring.
