
Date: 30-06-2025

# Connection-oriented and Connectionless Protocols

Another way in which networks and protocols are differentiated is by whether they use connection between a device or not. This is a concept that is close linked with [[Switching Methods|packet and circuit switching]].

## Connection-Oriented protocols

As inferred from the name, for the data transfer to happen, a connection must be established between both of the system. This is governed by a set of rules that say how a connection should be initiated, negotiated, maintained and get terminated.

Usually it happens by one of the device sending a request to the other device to open a connection.

## Connectionless Protocols

These protocols do not establish a connection. When a device has a data to send, it just sends it over the internet.

## Relationship between Connection-oriented and Circuit-switched network

[[Switching Methods|Circuit-switched]] networking are inherently connection-oriented, but not all the connection-oriented networks are circuit-switched. A connection is needed for a circuit for passing data, but a circuit is not a prerequisite to establish a connection.


Connection-oriented networks are important because they enable the implementation of applications that require connections. 

**For example:** To send files over the network, we need the [[FTP]] protocol from the [[TCP and IP|TCP/IP]], you have to connect to a server, enter the credentials and send or retrieve data. Similary, we have [[Telnet]] which requires to be connected to a system for remote access. 

Both of the above examples, work above the IP protocol, which uses packets as the mode of data transfer, through the concept of [[Layering|layering]].

Back to parent node: [[Networking]]