[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 9

## Topics covered
*What topics were covered in this session*

Intoduction to Networking.

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

The field of computer networking began in the early 1960s with the introduction of packet-switched networking, which allowed messages to be divided into packets and routed independently through a network, a concept first described by Leonard Kleinrock at UCLA. Early mainframe computers relied on point-to-point or point-to-multipoint links, with remote terminal controllers and card readers acting as peripherals under the control of the central mainframe. As computing evolved, peer-to-peer and local area networks emerged, allowing independent systems to share information and collaborate more efficiently.

Network operating systems such as Novell NetWare and Microsoft NT were developed to enable multiple computers to share resources, and the process of load balancing and scaling allows complex tasks to be distributed among multiple machines for greater efficiency. The evolution of networking has led to the development of advanced paradigms such as Software-Defined Networking, which separates the network control plane from the data plane, improving network architecture and enabling dynamic programmability and updates. SDN’s centralized architecture provides a faster view of network status and increases network flexibility and performance. The SDN-OpenFlow paradigm allows network administrators to optimize services and security requirements, and supports the deployment of generic hardware devices that can be dynamically reconfigured via the software control plane.

The evolution of networking architectures has been marked by the transition from traditional static networks to programmable and virtualized environments, enabling greater flexibility, scalability, and cost efficiency. Modern paradigms such as Software-Defined Networking and Network Functions Virtualization have transformed network design and management by decoupling hardware and software components, allowing dynamic configuration and rapid deployment of network functions. In the context of the Internet of Things (IoT), SDN and NFV facilitate scalable, energy-efficient, and secure network operations, supporting the integration of heterogeneous devices and real-time data processing. The adoption of machine learning techniques in network softwarization addresses challenges in design, implementation, and security, enabling real-time optimization and adaptive protection against evolving threats.

(https://www.sciencedirect.com/topics/computer-science/networking-technology)

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

I completed exercises like choosing the best route in a router, a router recieves a packet destined for an address that matches three different routes in its routing table. The router must select the route with the longest and most specific prefix. Even though one route covers a large network and another covers a medium sized one, the third route contains the most specific prefix length. Because routers always choose the most specific match, the packet is forwarded along that route, ensuring the most precise and efficient delivery. And i also tried identifying the correct transport protocol, this is a user that tries to determine whether TCP or UPD is better for different applications. When examing video conferencing traffic, the user realizes that speed is more important than guaranteed delivery, meaning a few lost packets will not break the conversation. Therefore, UPD is more suitable. However, when downloading a large file, every packet must arrive intact and in the correct order, so TCP is preffered because it provides reliability and retransmission.

## Summary of learning
*What did you learn through these exercises*

I learned that routers decide where to send packets by selecting the most specific matching route in their table. This process is called longest prefix match, when multiple routes overlap, the router chooses the one with the longest subnet mask because it represents the most precise destination. For example, if a packet is adressed to a network that appears in entries with masks /16, /24, and /28, the router will always pick the /28 route. Even if other routes have lower cost or different next hops, prefix length takes priority, this ensures accurate, efficient, and predictable packet forwarding.
