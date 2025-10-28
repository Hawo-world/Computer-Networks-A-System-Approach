# 🧭 3.1 Problem: Not All Networks Are Directly Connected

## 🌐 Summary

### 🌍 The Challenge: Building Global Networks

Individual network technologies—like Ethernet, Wi-Fi, or point-to-point links—can only connect a limited number of devices or cover limited distances. For example:

- **Ethernet:** connects up to 1024 hosts  
- **Point-to-point links:** connect only two nodes  
- **Wireless networks:** limited by radio range  

To create a **global-scale network**, we must **interconnect many smaller, heterogeneous networks** built from these different technologies.  
This process is called **internetworking**, the **core principle behind the Internet**.

---

## ⚙️ Subproblems of Internetworking

Internetworking introduces several challenges that must be solved at different layers of the network architecture.

### 1. Interconnecting Similar Links (Switching)

- Devices connecting **links of the same type** are called **switches** or **Layer 2 (L2) switches**.  
- A special L2 switch for Ethernet networks is a **bridge**.  
- The switch’s job is to **forward (switch)** packets to the correct output port.  
- Forwarding can be:
  - **Connectionless** (e.g., Ethernet, IP): each packet is independent.  
  - **Connection-oriented** (e.g., ATM, MPLS): a virtual connection is set up first.

---

### 2. Interconnecting Different Networks (Routing)

- To connect **different types of networks**, we use **routers** (a.k.a. **Layer 3 (L3) switches**).  
- Historically called **gateways**, routers handle differences in addressing, packet size, and protocol.  
- The **Internet Protocol (IP)** was designed to enable interconnection across diverse technologies.

---

### 3. Finding Efficient Paths (Routing Algorithms)

- With many routers and links, there are multiple possible paths between any two points.  
- Routing determines the **best path** for packets, ensuring routes are:
  - **Efficient** (low cost or short distance)  
  - **Loop-free** (no infinite forwarding)  
  - **Adaptive** (able to adjust to failures or changes)  

Routing algorithms and protocols are therefore essential to network scalability and reliability.

---

### 4. Implementing Switches and Routers

- **Switches** and **routers** are physical devices implementing these functions.  
- They can be built using:
  - **General-purpose computers** for flexibility.  
  - **Specialized hardware** for high-speed backbone performance.  
- High-end routers must support **massive switching capacity** to handle global Internet traffic.

---

## 💡 Big Picture

Internetworking unites **switches, routers, protocols, and routing algorithms** into a **scalable, fault-tolerant Internet**.  
Without this modular architecture, we would only have isolated local networks instead of today’s interconnected global system.

---

## 🧾 Glossary

| Term | Definition |
|------|-------------|
| **Internetworking** | Connecting multiple diverse networks into one unified Internet. |
| **Switch (L2 Switch)** | Connects links of the same type and forwards packets within a LAN. |
| **Bridge** | A switch used specifically to connect Ethernet segments. |
| **Router (L3 Switch)** | Connects different networks and routes packets between them. |
| **Gateway** | Older term for a router; connects different network types. |
| **Layer 2 (L2)** | Data Link layer responsible for local frame delivery. |
| **Layer 3 (L3)** | Network layer responsible for routing across networks. |
| **Connectionless Forwarding** | Each packet is forwarded independently (e.g., IP). |
| **Connection-Oriented Forwarding** | A virtual circuit is established before transmission. |
| **Internet Protocol (IP)** | The universal Layer 3 protocol enabling global internetworking. |
| **Routing** | Finding a path for packets through one or more networks. |
| **Routing Algorithm** | Determines efficient, loop-free, adaptive routes for packets. |
| **Packet Switching** | Divides data into packets sent independently across a network. |
| **Heterogeneity** | Diversity of network technologies, media, and protocols that interoperate in the Internet. |
