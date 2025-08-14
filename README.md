Retail Store POS Network
📌 Overview

This project simulates a secure small-scale retail store network using Cisco Packet Tracer.
The design ensures traffic isolation between Point-of-Sale (POS) and Customer networks while maintaining internet access for both.
Key features include NAT, DHCP, DNS, and Static Routing for reliable and secure operations.

🛠 Features

POS–Customer Traffic Isolation using Access Control Lists (ACL)

NAT Overload for internet access from private networks

DHCP for automatic IP configuration

DNS for internal and external name resolution

Static Routing for predictable network paths

Secure & Scalable network design for small businesses

📂 Project Structure
Retail_Store_POS_Network/
│
├── Topology_Screenshot.png      # Network topology diagram
├── Router_Configure.txt         # Router CLI configurations
├── README.md                    # Project documentation
└── Testing_Results.txt          # Ping, DNS, NAT, and isolation tests

📷 Network Topology


Figure: Retail Store POS Network with separate POS and Customer sections, Manager/Control Center, Server Room, and ISP connections.

⚙️ Used Technologies

VLSM (Variable Length Subnet Masking) – Efficient IP allocation

Static Routing – Manual route configuration for stability

NAT Overload – Internet access from internal networks

DHCP – Automatic IP assignment for clients

DNS – Resolves domain names to IP addresses

ACL – Blocks unauthorized access between networks

✅ Testing & Verification
Test	Source	Destination	Expected Result
LAN Connectivity	POS PC → POS PC	Ping Success	✅
Isolation Test	Customer PC → POS PC	Ping Blocked	✅
NAT Test	POS PC → External Server	Ping Success	✅
DNS Test	POS PC → inventory.local	Resolves to 192.168.10.20	✅
DNS Test	Customer PC → inventory.global	Resolves to 203.0.113.10	✅
📜 How to Use

Open the .pkt file in Cisco Packet Tracer.

Check device IP configurations.

Test connectivity using ping, nslookup, and browser access.

Review router configurations in Router_Configure.txt.

🏆 Project Outcome

Securely separates POS and customer traffic.

Provides reliable internet access to both networks.

Demonstrates core networking concepts in a practical scenario.

📚 References

Cisco Networking Academy – Networking Essentials

Packet Tracer Official Documentation

Small Business Network Security Guidelines
