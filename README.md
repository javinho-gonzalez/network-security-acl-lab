**Network Security Lab – ACL Implementation (Cisco Packet Tracer)**

Beginner network security project demonstrating practical ACL implementation and traffic filtering

**Objective**

The goal of this project was to simulate a network environment and implement Access Control Lists (ACLs) to control traffic between different subnets based on security policies.



**Scenario**

In this lab, multiple networks were configured and connected through routers using EIGRP routing. Specific security policies were defined to restrict communication between certain subnets while allowing all other traffic.



**Network Policies Implemented**

•Network 192.168.11.0/24 is denied access to the Web Server (192.168.20.254)

•Network 192.168.10.0/24 is denied communication with network 192.168.30.0/24

•All other traffic is allowed



**What I Implemented**

•Configured IP addressing across multiple networks

•Verified full connectivity before applying security rules

•Created standard ACLs on routers (R2 and R3)

•Applied ACLs to outbound interfaces

•Tested connectivity to validate security policies



**Verification \& Testing**

•The following tests were performed:

•Allowed traffic between authorized networks

•Blocked traffic according to defined policies

•Verified ACL matches using show access-lists



**Key Concepts Demonstrated**

•Access Control Lists (ACLs)

•Network segmentation

•Traffic filtering

•Basic network security enforcement

•Routing with EIGRP



**Tools Used**

•Cisco Packet Tracer


**What I Learned**

•How ACLs control traffic flow

•Importance of testing before applying rules

•How misconfigured ACLs can block legitimate traffic

•How to validate configurations using logs and connectivity tests
