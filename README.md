Network Dashboard Project (DNS + HTTP)
Cisco Packet Tracer | Networking Fundamentals
📌 Project Overview
This project demonstrates a simulated network environment built using Cisco Packet Tracer, focusing on how core network services interact in a real‑world setup.
The goal was to understand and implement DNS name resolution, HTTP web services, DHCP, and multi‑device connectivity, while troubleshooting common networking issues along the way.
This project builds on earlier work involving Windows Server RRAS VPN configuration, as part of a structured learning path into networking and infrastructure fundamentals.

🖧 Network Topology
The network consists of:

Wired PC client
Wireless laptop client
Network printer
Switch (Layer 2 connectivity)
Wireless router
DNS + HTTP server

All devices are connected within a single LAN and communicate using automatically assigned IP addresses via DHCP.
📷 See screenshots for full topology and connectivity validation.

🔧 Technologies & Concepts Used

Cisco Packet Tracer
DNS (Domain Name System)
HTTP Web Server
DHCP (Dynamic Host Configuration Protocol)
Wired & Wireless Networking
Client–Server Communication
Basic Network Troubleshooting
HTML / CSS (custom web dashboard)


✅ Key Features

🔹 DNS configured to resolve a custom domain name (mywebsite.com)
🔹 HTTP server hosting a custom-built dashboard-style website
🔹 DHCP providing automatic IP addressing to all clients
🔹 Successful domain-based access to the website from multiple devices
🔹 Mixed wired and wireless client connectivity
🔹 Printer integrated into the network
🔹 Dashboard-style web interface simulating an admin panel


🧪 Testing & Validation
<img width="650" height="307" alt="image" src="https://github.com/user-attachments/assets/929b8cdf-eeef-4369-baca-77d156bbea46" />

DNS resolution verified using ping mywebsite.com
HTTP access confirmed via web browser on multiple clients
End-to-end connectivity tested across all devices
DHCP lease assignment validated on clients

Screenshots included in this repository show:

Network topology
DNS resolution results
HTTP dashboard in use


⚙️ Challenges & Learning Outcomes
One of the key challenges was troubleshooting DHCP failures and connectivity issues between devices. Resolving these issues helped reinforce:

The dependency between network services
The importance of correct interface and service configuration
How DNS, DHCP, and HTTP interact in layered network communication


🚀 Next Steps
This project serves as a foundation for more advanced networking topics, including:

VLANs and network segmentation
Inter‑VLAN routing
Access Control Lists (ACLs)
Network security policies

These are explored in subsequent projects.

---

## 📂 Repository Contents

- `/screenshots` – Network topology, DNS tests, and web interface screenshots  
- `/website` – HTML/CSS files for the dashboard interface  
- `README.md` – Project documentation  

---

## 👤 Author

**Samie Ullah**  
Aspiring IT / Network Professional  

Learning networking fundamentals through hands‑on labs, troubleshooting, and clear technical documentation.
