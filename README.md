# Home Network Audit

This project documents a complete assessment of a home network environment, including device inventory, network topology, connectivity testing, and security review.

## Skills Demonstrated

- TCP/IP Networking
- Network Documentation
- Troubleshooting
- Security Assessment
- Technical Writing
- Network+ Concepts

# Deliverables
## 1. Network Connections

Documented every device connected to the network.

| Device     | Type          | IP Address    | Connection |
| ---------- | ------------- | ------------- | ---------- |
| Desktop PC | Workstation   | 192.168.1.100 | Ethernet   |
| Laptop     | Workstation   | 192.168.1.101 | Wi-Fi      |
| Smartphone | Mobile Device | 192.168.1.102 | Wi-Fi      |
| Printer    | Printer       | 192.168.1.103 | Wi-Fi      |


You can gather this information from:

1. Router admin page
2. arp -a
3. ipconfig

## 2. Network Diagram (drawn via free tool https://www.diagrams.net?utm_source=chatgpt.com)

<img width="2044" height="1764" alt="image" src="https://github.com/user-attachments/assets/9e733b5b-b742-47e4-812f-ae068065a8c1" />



## 3. IP Config Analysis
Run in cmd:
ipconfig /all

Document:

- IPv4 address: Identifies devices on a network.
- Subnet mask: Used to divide a larger network into smaller networks, called subnets, that aid in network efficiency, security, and improved performance.
- Default gateway: Used to connect networks all over.
- DNS servers: Specialized computers that help web browsers, applications and other network tools locate and connect with websites and other resources on the internet.

