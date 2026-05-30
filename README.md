# Open-Shortest-Path-First-OSPF-
## What is OSPF? 
Open Shortest Path First (OSPF) is a dynamic routing protocol used in Internet Protocol (IP) networks. It is classified as a Link State Routing Protocol and is widely used in enterprise networks because of its fast convergence, scalability, and efficient routing capabilities.

OSPF was developed by the Internet Engineering Task Force (IETF) as an open standard routing protocol. It is defined in RFC 2328 for IPv4 and OSPFv3 for IPv6. 

Unlike distance vector protocols such as RIP, OSPF maintains a complete map of the network topology and calculates the shortest path using Dijkstra’s Shortest Path First (SPF) algorithm. 

<img width="868" height="570" alt="Screenshot 2026-05-30 200337" src="https://github.com/user-attachments/assets/1a224ede-a2d4-419d-92b9-f91f466b18d0" />

<img width="585" height="728" alt="Screenshot 2026-05-30 202034" src="https://github.com/user-attachments/assets/dd44c141-472a-4081-b2a5-181efe8d5bc3" />

## Features of OSPF 
* Open standard protocol 
* Supports large enterprise networks 
* Fast convergence 
* Classless routing protocol
* Supports VLSM and CIDR 
* Uses cost as metric 
* Supports load balancing 
* Hierarchical routing using areas 
* Authentication support 
* Efficient routing updates

## Why OSPF is Preferred? 
OSPF is preferred in modern networks because:

1. It converges faster than RIP. 
2. It supports large networks. 
3. It avoids routing loops. 
4. It efficiently utilizes bandwidth. 
5. It supports hierarchical network design.
   


## Working Principle of OSPF 
OSPF operates by exchanging link-state information between routers. Every router creates a map of the network and independently calculates the shortest path. 

* The operation of OSPF can be divided into the following steps: 
* Neighbor discovery 
* Adjacency formation 
* Exchange of link-state advertisements 
* Building Link State Database (LSDB) 
* Running SPF algorithm 
* Updating routing table

## Output: 
<img width="1920" height="1080" alt="Screenshot 2026-05-30 215008" src="https://github.com/user-attachments/assets/f7eec31d-57ba-4ecb-8e80-c3ccbe2f07ae" />

## Conclusion  
OSPF is a robust and highly efficient routing protocol suitable for medium and large-scale networks. Its 
advanced features such as hierarchical design, fast convergence, authentication, and scalability make it a 
preferred choice for enterprise and service provider environments.  
Understanding OSPF concepts, configuration, and troubleshooting techniques is essential for networking 
students, engineers, and administrators. 


