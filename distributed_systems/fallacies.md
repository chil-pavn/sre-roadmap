# Fallacy 1: The network is reliable:
- Basic switches have MTBFs, but power failures and hardware/software failures pose risks.
- Infrastructure and software redundancy is vital to address the network's unreliability.

# Fallacy 2: Latency is zero:
- Latency increases significantly in WAN and internet scenarios, impacting system performance.
- Considering latency is crucial to minimize fine-grained calls and optimize data transfer.

# Fallacy 3: Bandwidth is infinite:
- While bandwidth grows, the increasing amount of data and packet loss continue to impact network performance.
- Factors like VoIP, videos, and reliance on verbose formats contribute to bandwidth limitations.

# Fallacy 4: The network is secure:
- Assuming network security leads to vulnerability to security threats like DDOS attacks.
- Implementing strong security measures, such as encryption and authentication, is essential for network protection.

# Fallacy 5: Topology doesn't change:
- Assuming static network topology ignores changes caused by system updates, expansions, or failures.
- Dynamic network monitoring and adaptive design are essential to accommodate changes in network topology.

# Fallacy 6: There is one administrator:
- Depending on a single administrator leads to the risk of single points of failure in network management.
- Implementing distributed network management and access controls is necessary to mitigate the risks.

# Fallacy 7: Transport cost is zero:
- Neglecting transport costs results in underestimating the impact of network traffic and infrastructure usage.
- Accounting for transport costs is crucial for optimizing resource allocation and network efficiency.

# Fallacy 8: The network is homogeneous:
- Assuming network homogeneity neglects the diversity of devices, protocols, and technologies in the network environment.
- Adopting flexible and compatible network designs is essential to support heterogeneous network components.

# Key Points to keep in mind to counter the above fallacies:

*_TCP Throughput and Bandwidth Limitations:_
- TCP throughput is bounded by factors like round trip time, packet loss, and frame size.
- Bandwidth limitations necessitate limiting the size of data sent over the network.

*_Network Security Fallacies and Statistics:_
- Network security fallacies persist despite widespread acknowledgment of its importance.
- Statistics reveal ongoing challenges in maintaining network security.

*_Implications of Network (In)Security:_
- Security needs to be integrated into architectural planning from the start.
- Threat modeling and risk evaluation are essential in determining security measures.

*_Network Topology and Application Dependencies:_
- Network topology changes frequently in production environments.
- Applications should avoid depending on specific endpoints or routes and consider location transparency.

*_Challenges of Multiple Administrators:_
- Enterprise systems often involve multiple administrators with differing expertise and agendas.
- In situations involving external entities or services, administrators may not be under the application owner's control.

*_Need for Problem Identification and Solutions:_
- Identifying and solving problems in distributed systems is crucial for successful application deployment.
- Changes in hosting services may require reworking applications to ensure compatibility.

*_Administrator Tools and Proactive Monitoring:_
- Providing administrators with diagnostic tools is essential for problem identification and resolution.
- Including monitoring tools allows for early problem detection and preventing system failures.

*_Challenges with Multiple Administrators:_
- Multiple administrators can limit application options and need effective management support.
- Considerations for upgrades and backward/forward compatibility are essential in multi-administrator environments.

*_Transport Cost Fallacy:_
- The fallacy of zero transport cost is debunked, emphasizing the need to consider costs for network operation and maintenance.
- Even existing solutions may be constrained by the costs involved, underscoring the importance of cost-effective problem-solving.

*_Heterogeneity of Networks:_
- Assuming network homogeneity is a fallacy, necessitating readiness for interoperability and support for standard technologies.
- Consideration of proprietary protocols and transports should be approached with caution in heterogeneous enterprise environments.

*_Persistent Challenges in Distributed Systems:_
- Despite advancements in technology, the underlying problems and characteristics of distributed systems remain largely unchanged.
- Neglecting the issues covered by the fallacies can lead to problems resurfacing and impacting application stability.


References:

[Architecture Notes](https://architecturenotes.co/fallacies-of-distributed-systems/)

[Wikipedia](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing#:~:text=The%20fallacies%20of%20distributed%20computing,to%20distributed%20applications%20invariably%20make)

[Research Gate](https://www.researchgate.net/publication/322500050_Fallacies_of_Distributed_Computing_Explained/link/5a5c8391aca2727d608a8830/download?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIn19)

[Ably](https://ably.com/blog/8-fallacies-of-distributed-computing)

[Medium](https://medium.com/geekculture/the-eight-fallacies-of-distributed-computing-44d766345ddb)

[Oracle](https://blogs.oracle.com/developers/post/fallacies-of-distributed-systems)