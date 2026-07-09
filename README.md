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
   <img width="462" height="462" alt="arp -a" src="https://github.com/user-attachments/assets/edfffb18-4bac-408c-8776-7d8252cf5b03" />
4. ipconfig
   <img width="282" height="618" alt="ipconfig" src="https://github.com/user-attachments/assets/bb8f35de-7f87-4c4c-a783-48af45ec8643" />



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

## 4. Connectivity Testing
Perform tests in cmd:
- ping 8.8.8.8
- ping google.com
- tracert google.com
<img width="837" height="750" alt="tracert" src="https://github.com/user-attachments/assets/f197f064-ecb1-426b-ad5f-4523094d3a3e" />


Document:
- Ping successful
- Response time is about 25ms on average
- Route traced to google.com over 30 hops. About half of them timed out.


## 5. Wireless Security Assessment 
Review:
- Wi-Fi encryption type: Wi-Fi 6 (802.11ax)
- Guest network status: Off
- Default passwords changed? Yes
- Firmware updates available? No
<img width="627" height="826" alt="router" src="https://github.com/user-attachments/assets/6210931e-17da-4f28-9287-72f21b23fe7f" />


## 6. Performance Testing

Tools Used:

- Task Manager
- Resource Monitor

Run speed tests and record 

- Download speed:1065.8 Mbps
- Upload speed:19.1 Mbps
- Latency:36 ms
<img width="782" height="517" alt="speedtest" src="https://github.com/user-attachments/assets/b18a8691-b32b-4823-8a52-21e0bac1c090" />



