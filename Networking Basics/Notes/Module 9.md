# Module 9 - IPv4 and Network Segmentation

**Course:** Cisco Networking Academy – Networking Basics  
**Module:** 9 - IPv4 and Network Segmentation

---

# Module Overview

This module introduced different IPv4 communication methods, types of IPv4 addresses, and why network segmentation is important in modern networks. It also explained how broadcasts affect network performance and how subnetting improves efficiency and security.

---

# IPv4 Communication Methods

IPv4 supports three communication methods.

## 1. Unicast

Unicast is **one-to-one communication**.

A packet is sent from one source device to one specific destination device.

Examples:

- Browsing websites
- SSH
- Email
- File downloads

Most internet traffic uses unicast communication.

---

## 2. Broadcast

Broadcast is **one-to-all communication**.

A packet is delivered to every device within the same broadcast domain.

Important points:

- Routers do not forward broadcast packets.
- Used for network discovery.
- Commonly used by ARP and DHCP.

---

## 3. Multicast

Multicast is **one-to-many communication**.

Packets are delivered only to devices that have joined a multicast group.

Examples:

- IPTV
- Live video streaming
- Video conferencing
- Online meetings

Compared to broadcast, multicast saves bandwidth.

---

# Communication Comparison

| Communication | Description | Receivers |
|--------------|-------------|-----------|
| Unicast | One → One | Single device |
| Broadcast | One → All | Every device in the local network |
| Multicast | One → Many | Devices subscribed to a multicast group |

---

# Types of IPv4 Addresses

## Public IPv4 Address

A public IPv4 address is globally routable on the Internet.

Characteristics:

- Unique worldwide
- Assigned by an ISP
- Used for Internet communication

---

## Private IPv4 Address

Private IPv4 addresses are used inside local networks.

Private address ranges:

- **10.0.0.0 – 10.255.255.255**
- **172.16.0.0 – 172.31.255.255**
- **192.168.0.0 – 192.168.255.255**

Characteristics:

- Not routable on the Internet
- Used in homes and organizations
- Require NAT to communicate over the Internet

---

## Loopback Address

Loopback addresses are reserved for testing the local device.

Range:

```
127.0.0.0/8
```

Most commonly used:

```
127.0.0.1
```

Purpose:

- Tests the TCP/IP stack
- Sends traffic back to the same device

---

## Link-Local (APIPA) Address

Range:

```
169.254.0.0/16
```

Assigned automatically when:

- A DHCP server is unavailable.
- The device cannot obtain an IP address.

---

# IPv4 Address Classes

Earlier IPv4 networks were divided into classes.

### Class A

- Range: 0.0.0.0 – 127.255.255.255
- Supports very large networks

---

### Class B

- Range: 128.0.0.0 – 191.255.255.255
- Supports medium to large networks

---

### Class C

- Range: 192.0.0.0 – 223.255.255.255
- Supports small networks

---

### Class D

- Range: 224.0.0.0 – 239.255.255.255
- Reserved for Multicast

---

### Class E

- Range: 240.0.0.0 – 255.255.255.255
- Reserved for Experimental use

---

# NAT (Network Address Translation)

Organizations commonly use private IPv4 addresses internally.

Before traffic reaches the Internet, NAT translates the private IPv4 address into a public IPv4 address.

Benefits:

- Conserves public IPv4 addresses
- Improves security by hiding internal IP addresses

---

# Broadcast Domains

A broadcast domain is the portion of a network where broadcast packets are received.

Examples of broadcast traffic:

- ARP Requests
- DHCP Discover messages

Large broadcast domains generate excessive traffic, reducing network performance.

---

# Network Segmentation

Network segmentation divides one large network into multiple smaller networks.

These smaller networks are called **subnets**.

Benefits:

- Reduces broadcast traffic
- Improves performance
- Easier troubleshooting
- Better security
- Simplifies network management

---

# Subnetting

Subnetting creates multiple logical networks from a single network by borrowing host bits.

Advantages:

- Better utilization of IPv4 addresses
- Smaller broadcast domains
- Improved network efficiency
- Better traffic control

---

# Role of Routers

Routers connect different networks together.

They:

- Forward packets between networks
- Prevent broadcasts from crossing network boundaries
- Enable communication between different subnets

---

# Key Terms Learned

- IPv4
- Public IP
- Private IP
- Loopback Address
- APIPA
- NAT
- Unicast
- Broadcast
- Multicast
- Broadcast Domain
- Router
- Subnet
- Subnetting

---

# Key Takeaways

- IPv4 supports Unicast, Broadcast, and Multicast communication.
- Public IP addresses are globally routable, while private IP addresses are used within local networks.
- NAT allows private networks to communicate with the Internet.
- Loopback addresses are used for local testing.
- APIPA addresses are automatically assigned when DHCP is unavailable.
- Large broadcast domains reduce network performance.
- Subnetting creates smaller, more efficient networks.
- Routers connect networks and block broadcast traffic between subnets.

---

# Reflection

This module gave me a solid understanding of how IPv4 communication works in enterprise networks. Learning about public and private addressing, NAT, broadcast domains, and subnetting showed how organizations design networks that are efficient, scalable, and secure. These networking fundamentals are directly applicable to SOC analysis, network troubleshooting, and penetration testing.

---

