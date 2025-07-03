Date: 03-07-2025

# Messages

Many of the networking technologies use [[Switching Methods|packet switching]], which means sending small chunks of data from one system to another. But usually in networks, sending data between networking devices is generically called **messaging** and packets are one such way of calling a message. 

The type of the name that is used, usually says about the type of data that is carried. They are also usually associated with the protocols and technologies operating at different layers of the [[OSI Model|OSI Reference Model]].

Different types of names:
- [[Packet]]
- [[Frames]]
- [[Datagrams]]
- [[Cells]]

# Message Formatting

When it comes to messages, they do not differ not in the way they are called as in different names, but in the content they carry.

**For example:** 

The message that is used in connecting a web server to a web browser vary completely different from a message that connects ethernet cards. So, formatting the messages that are sent helps in differentiating between messages.

Different types of formatting:
- [[Header]]
- [[Data]]
- [[Footer]]

![formatting](formatting.png)

### Header

The header is usually a small number of bytes of control information. It says important facts about the data that is sent and how it is to be interpreted. They act as the control link between different protocol devices

### Footer

Footer is pretty much the same as the header and it covers the data to be sent just as shown in the picture

### Data

They are the actual data that are transmitted, they are also called as the **payload** of the message. There are some data which contain no information, they are usually used in starting or terminating a logical connection between the devices.


Back to parent node: [[Networking]]