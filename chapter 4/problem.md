# 🌍 Problem: Scaling to Billions

## Summary

As computer networks expanded into the global Internet, the central challenge shifted from connecting *different kinds* of networks (heterogeneity) to making that vast system *scale*.  
The Internet’s exponential growth—doubling in size nearly every year for decades—has required new strategies to manage billions of nodes and hundreds of thousands of interconnected networks.

The **core scalability challenge** lies in **routing**: how to efficiently compute and manage paths across such an enormous, dynamic system.  
The solution has been to introduce **hierarchy**, both *within networks* (using areas and domains) and *between networks* (interdomain routing).  
The **Border Gateway Protocol (BGP)** is the key mechanism that enables this hierarchical, scalable interconnection of autonomous networks.

A related issue is **addressing**.  
The original 32-bit IPv4 address space has proven insufficient for the Internet’s growth, leading to the design of **IPv6**, which provides vastly more addresses and introduces several architectural improvements.

Beyond growth in size, the Internet has also evolved in *functionality*.  
Three major innovations help it scale in new directions:

1. **Multicast** – Efficiently delivers the same data to many receivers simultaneously.  
2. **MPLS (Multiprotocol Label Switching)** – Adds label-based forwarding for flexibility and performance.  
3. **Mobility Support** – Extends IP to accommodate mobile hosts and routers that change locations while maintaining connectivity.

Each of these advances—**routing hierarchy**, **IPv6**, **multicast**, **MPLS**, and **mobility**—addresses aspects of the same overarching issue:

> **How to scale the Internet to billions of users, devices, and dynamic connections while preserving efficiency, reliability, and adaptability.**

---

## 📘 Glossary

| **Term** | **Definition** |
|-----------|----------------|
| **Scalability** | The ability of a network to grow in size and complexity without performance degradation. |
| **Routing Hierarchy** | Structured division of networks into regions or layers to simplify routing and reduce complexity. |
| **BGP (Border Gateway Protocol)** | The main interdomain routing protocol connecting autonomous systems (AS) across the Internet. |
| **IPv4 (Internet Protocol version 4)** | The original 32-bit Internet addressing system, supporting ~4.3 billion unique addresses. |
| **IPv6 (Internet Protocol version 6)** | Successor to IPv4 with 128-bit addresses, vastly expanding address space and features. |
| **Multicast** | Method for efficient delivery of the same data to multiple recipients simultaneously. |
| **MPLS (Multiprotocol Label Switching)** | Technique using short labels instead of full IP lookups for faster, more flexible routing. |
| **Mobility Support** | Enhancements to IP allowing devices to move between networks while maintaining active connections. |
| **Heterogeneity** | Diversity of network technologies (wired, wireless, etc.) interconnected within the Internet. |

---

✅ **Summary Complete — Problem: Scaling to Billions**
