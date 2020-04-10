# Computer Network & Network Reference Model

## Overview of Computer Network

### Networks
+ What is a network?
    + A network is an intricately connected system of objects,devices, or people
+ Companies created networks
    + As companies expanded, the need for connecting network at different sites became very important
  
### Data Networks Classifications
+ LAN(Local Area Networks)
+ WAN(Wide Area Networks)

### LAN/WAN

+ Local Area Networks(LANs)
    + Operate locally(cover small areas)
    + Multi-user access
    + High speeds expected(up to Gbps/10Gbps)
    + Error rae is easily controlled
+ Wide Area Networks(WANs)
    + Operate over larger areas
    + Access over serial links,optical links, etc
    + Traditionally, have Lower speeds
    + Error rate can not be easily controlled

### Internet

+ internet：
    + A network whose nodes are networks
+ Internet
    + The largest, open, interconnected computer network in the world
    + TCP/IP is the reference model of Internet
    + Evolved from ARPANET

### Internet with Multi-layer ISP structure
+ Internet Service Provides(ISP)

### LAN Devices
+ Hub-Multiport repeater,connects PCs; Repeats signals
+ Bridge-LAN segmentation; MAC addresses
+ Switch-Multi-bridge; Full bandwidth
+ Router-Path determination; Packet switch


### WAN Devices
+ Router-Path determination; Packet switching
+ Modem CSU/DSU TA/NT1- Analog to digital; Remote LAN connections

### LAN Services and WAN Services
> 待补充
### Data
> 待补充
### Protocol
> 待补充
### Data Packets
> 待补充
### Source and Destination
> 待补充
### Media Types
> 待补充
### Digital Bandwidth
> 待补充
### Throughput
> 待补充

## OSI Reference Model

### OSI(Open System Interconnection) Model
+ Proposed by International Organization for Standardization (ISO)
+ A network model that help network builders implement networks that could communicate and work together
+ Describes how information or data moves from one computer through a network to another computer
+ a layered communication process
    + Each layer performs a specific task
  
### The OSI Reference Model
Each layer has a unique function
```
7. Application   -> User interface
6. Presentation  -> Data presentation and encryption
5. Session       -> Inter-host connection
4. Transport     -> End-to-end connections
3. Network       -> Addresses and best path
2. Data Link     -> Access to media
1. Physical      -> Binary transmission
```

### Why a Layered Model?
+ Reduce Complexity
+ standardizes interfaces
+ Facilitates modular engineering
+ Ensures interoperable technology
+ Accelerates evolution
+ Simplifies teaching and learning

### The OSI Reference Model

## TCP/IP
### The TCP/IP Model
+ The U.S Department of Defense(DoD) created the TCP/IP reference model
+ The DoD wants its packets to get through every time,under any conditions, from any one point to any other point
+ It brought about the creation of the TCP/IP model
+ TCP/IP model has since become the standard on which the Internet has grown

### The TCP/IP Model
* The TCP/IP model has only four years

```
Application
Transport
Internet
Network Access
```

### The TCP/IP Model - pplication Layer
+ Handles high-level protocols, issues of represenetation, encoding, and session control
+ TCP/IP combines all application-related issues into one layer,and assures this data is properly packaged fir the next layer

### The TCP/IP Model - Transport Layer

### The TCP/IP Model - Internet Layer

### The TCP/IP Model - Network Access Layer

### Common TCP/IP Protocals

### Similarities of TCP/IP and OSI

### Differences of TCP/IP and OSI


## Network Topology
### Topology

### Network Topologies
+ Bus
+ Ring
+ Star
+ Extened Star
+ Hierarchical
+ Mesh
## Network Devices

### LAN Devices in a Topology

### LAN Devices in a Topology

### NICs - Layer 2

### Media - Layer 1

### Repeaters - Layer 1

### Hubs - Layer 1

### Repeaters/Hubs - Dfferences

### Hub


### Bridges - Layer 2

### Switches - Layer 2

### Routers - Layer 3

### Clouds - Layers 1-7

### Evolution of Networking Devices and the OSI Layers

### Paclet Flow Through Clouds

