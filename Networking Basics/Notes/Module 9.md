# Module 9 - IPv4 Communication

**Course:** Cisco Networking Academy - Networking Basics  
**Module:** IPv4 Communication

---

# What I Learned

This module introduced how devices communicate using IPv4 addresses and the different methods used to deliver data across a network. I also learned how IPv4 communication works efficiently by using different transmission methods depending on the destination.

---

# IPv4 Communication Types

IPv4 devices communicate using three primary methods:

- Unicast
- Broadcast
- Multicast

Each method serves a different purpose within a network.

---

## Unicast

Unicast is **one-to-one communication**.

A packet is sent from one device directly to another specific device using its unique IPv4 address.

Examples:

- Browsing a website
- SSH connection
- Downloading files
- Sending emails

Most internet traffic uses unicast communication.

---

## Broadcast

Broadcast is **one-to-all communication** within the same network.

One device sends a packet, and every host inside the local network receives it.

Important points:

- Broadcast traffic stays inside the local network.
- Routers do not forward broadcast packets.
- Used for device discovery and network services.

Example:

- ARP (Address Resolution Protocol) requests

---

## Multicast

Multicast is **one-to-many communication**.

Packets are delivered only to devices that have joined a multicast group instead of every device on the network.

Examples:

- Live video streaming
- IPTV
- Video conferencing
- Online classes

This method reduces unnecessary network traffic.

---

# IPv4 Communication Comparison

| Type | Communication | Receivers |
|------|---------------|-----------|
| Unicast | One → One | Single device |
| Broadcast | One → All | Every device in the local network |
| Multicast | One → Many | Devices subscribed to the multicast group |

---

# Broadcast Domains

A broadcast domain is the area where broadcast packets are received.

As networks grow larger:

- Broadcast traffic increases.
- Network performance decreases.
- Devices process more unnecessary traffic.

Limiting broadcast traffic improves overall network efficiency.

---

# Network Segmentation

Large networks are divided into smaller networks called **subnets**.

Network segmentation helps organizations by:

- Reducing broadcast traffic
- Improving network performance
- Making troubleshooting easier
- Increasing security
- Simplifying network management

Instead of placing every device in one network, devices are grouped based on departments, buildings, or specific functions.

---

# Role of a Router

Routers connect different networks and allow devices in separate subnets to communicate.

They also prevent broadcast traffic from crossing into other networks, helping control unnecessary traffic.

---

# Key Terms Learned

- IPv4
- Unicast
- Broadcast
- Multicast
- Broadcast Domain
- Subnet
- Network Segmentation
- Router

---

# Key Takeaways

- IPv4 supports Unicast, Broadcast, and Multicast communication.
- Unicast is the most common communication method.
- Broadcast reaches every device inside a local network.
- Multicast sends data only to interested devices, saving bandwidth.
- Large networks should be segmented into smaller subnets.
- Routers connect different networks and limit broadcast traffic.

---

# Reflection

This module strengthened my understanding of how IPv4 communication works in real-world networks. Learning the differences between Unicast, Broadcast, and Multicast, along with network segmentation, showed how organizations improve efficiency, performance, and security. These concepts are fundamental for networking and form an important foundation for cybersecurity, SOC analysis, and penetration testing.

---

**Module Status:** ✅ Completed