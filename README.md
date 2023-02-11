# OSI-Model

- It stands for Open Systems Interconnection Model.
- It has been developed by ISO - International Organization for Standardization in the year 1984.
- ISO is the organization & OSI is the model.
- It was the first standard model for network communications, adopted by all major computer and telecommunication companies.
- The purpose of the OSI reference model is
```
to demonstrate how to make it easier for systems to communicate without having to alter the underlying hardware or software's logic.
```
- the OSI model is not a protocol
- it is a model for understanding and designing a network architecture that is: flexible, robust and interoperable.
- It has 7 layers as follows: (Top to Bottom)
1. Application Layer
2. Presentation Layer
3. Session Layer
4. Transport Layer
5. Network Layer
6. Data-Link Layer
7. Physical Layer
- each layer has specific duties to perform and has to cooperate with the layers above and below it.

## Functionalities
- A message sent from device A to B has to pass through all 7 layers at A from top to down then all layers at B from bottom to top.
- As the message travel from device A to device B, it may pass through many intermediate nodes such as routers. These intermediate nodes usually involves only the first three layers of OSI model.
- Within a single machine, each layer calls upon the services of the layer just below it. Layer 3, for example, uses the services provided by layer 2 and provides services for layer 4. Betweeen machines, layer x on one machine communicates with layer x on another machine.
- The communication is governed by series of rules and conventions called protocols.

Transport - data divided into segments of data unit and source port and destination post number added process-process delivery.
Network -  here data is divided into packets and source ip and destinatin ip gets added to the message, source-destination delivery.
Data-Link Layer - here packets are divided into framges, source mac address and destinatin mac address are added to the message, this is hop-hop delivery.
Physical Layer - it divides the frames into bits and transfer over transimision medium, coaxial, fibre etc.