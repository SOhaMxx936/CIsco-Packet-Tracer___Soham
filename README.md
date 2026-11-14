# Cisco Packet Tracer – CN Lab

A collection of all the **Cisco Packet Tracer (`.pkt`) simulation files** created for the **Computer Networks (CN) Lab**. Each file is a self-contained network scenario that can be opened, simulated, and modified in Packet Tracer.

---

## Repository Contents

| # | File | Topic | What it demonstrates |
|---|------|-------|----------------------|
| 1 | `1.Simple Network and Topology.pkt` | Basic network & topology | Connecting end devices (PCs) through switches/hubs, basic IP addressing, and testing connectivity with `ping` |
| 2 | `2.Router networks.pkt` | Routers | Connecting multiple networks via routers, configuring router interfaces, and inter-network communication |
| 3 | `3.DHCP.pkt` | DHCP | Automatic IP address allocation to hosts using a DHCP server/pool |
| 4 | `4.Different servers.pkt` | Network servers | Setting up and accessing different services (such as DNS, HTTP/Web, FTP) on server devices |
| 5 | `5.Email Service.pkt` | Email service | Configuring a mail server (SMTP/POP3) and sending/receiving email between clients |
| 6 | `6.Static routing and VLAN.pkt` | Static routing & VLANs | Manual routes between networks and segmenting a LAN into VLANs |

---

## Requirements

- **Cisco Packet Tracer** (any recent version; 8.x recommended)
- A free Cisco Networking Academy account to download Packet Tracer: <https://www.netacad.com/>

---

## How to Use

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/SOhaMxx936/CIsco-Packet-Tracer___Soham.git
   ```
2. Open **Cisco Packet Tracer**.
3. Go to **File → Open** and select any `.pkt` file from the folder.
4. Switch to **Simulation mode** to watch packets move through the network, or use the **PC → Command Prompt** to run commands like `ping` and `ipconfig`.

---

## Lab Overview

### 1. Simple Network and Topology
The starting point of the lab: building a small LAN, placing end devices and a switch, and verifying that hosts can reach one another.

### 2. Router Networks
Extends the basic topology by joining separate networks through routers, introducing router interface configuration and default gateways.

### 3. DHCP
Shows how a DHCP server hands out IP configuration (address, subnet mask, gateway, DNS) automatically instead of configuring each host by hand.

### 4. Different Servers
Explores multiple server roles in one network, with clients accessing the services hosted on them.

### 5. Email Service
Sets up an email server and client accounts to demonstrate how mail is sent and received inside a network.

### 6. Static Routing and VLAN
Combines two core networking concepts: configuring static routes so routers know how to reach remote networks, and creating VLANs to logically separate traffic on a switch.

---

## Repository Structure

```
CIsco-Packet-Tracer___Soham/
├── 1.Simple Network and Topology.pkt
├── 2.Router networks.pkt
├── 3.DHCP.pkt
├── 4.Different servers.pkt
├── 5.Email Service.pkt
├── 6.Static routing and VLAN.pkt
└── README.md
```

---

## Author

**Soham** – B.Tech CSE student, Silicon University, Bhubaneswar
GitHub: [@SOhaMxx936](https://github.com/SOhaMxx936)

---

## Note

These files were created for academic lab work. Feel free to open them, explore the configurations, and use them as a reference for learning.
