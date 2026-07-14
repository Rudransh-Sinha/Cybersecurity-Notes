# Module 5 - Communication Principles

## Overview

In this module, I learned how devices communicate over a network using protocols, standards, and communication models. I also understood why every device on a network needs a unique identity and how data travels between devices using the TCP/IP and OSI models.

This module strengthened my networking fundamentals, which are essential before diving deeper into cybersecurity.

---

# Communication Protocols

A communication protocol is a set of rules that allows devices to exchange data correctly.

Without protocols, computers would not understand how to send or receive information.

### Why Protocols Matter

- Define how data is transmitted
- Ensure reliable communication
- Reduce communication errors
- Allow devices from different manufacturers to communicate

Examples:

- HTTP / HTTPS
- DNS
- DHCP
- FTP
- SSH
- SMTP

---

# Communication Standards

Standards make sure networking devices work together regardless of the manufacturer.

Organizations create these standards so that networks remain compatible worldwide.

### Common Standard Organizations

- IEEE
- IETF
- ISO
- ICANN

Example:

The **IEEE 802.11** standard defines how Wi-Fi communication works.

---

# Network Communication Models

Communication models explain how data moves from one device to another.

The two most common models are:

## OSI Model

The OSI model contains **7 layers**.

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

The OSI model is mainly used for learning and troubleshooting.

---

## TCP/IP Model

The TCP/IP model is the model used in real-world networking.

It has **4 layers**:

1. Network Access
2. Internet
3. Transport
4. Application

Most internet communication follows the TCP/IP model.

---

# How Devices See the Network

Every device connected to a network has its own identity.

A device may have:

- MAC Address
- IPv4 Address
- IPv6 Address
- Default Gateway
- DNS Server

Example:

```
IPv4 Address : 192.168.1.100
Default Gateway : 192.168.1.1
DNS Server : 8.8.8.8
```

These values allow the device to communicate with other devices and access the internet.

---

# IPv4 and IPv6

## IPv4

- 32-bit address
- Example: 192.168.1.100

## IPv6

- 128-bit address
- Larger address space
- Example:

```
2001:db8:acad:1::100/64
```

IPv6 was introduced because IPv4 addresses are limited.

---

# MAC Address

A MAC (Media Access Control) Address is the physical address assigned to a network interface.

Example:

```
70:2A:D5:BF:9B:C8
```

Characteristics:

- Unique for every network interface
- Used inside the local network
- Works at the Data Link Layer

---

# Default Gateway

The default gateway is the router that forwards traffic outside the local network.

Without a default gateway, a device can communicate only with devices on the same network.

Example:

```
192.168.1.1
```

---

# DNS (Domain Name System)

DNS converts human-readable domain names into IP addresses.

Instead of remembering:

```
142.250.xxx.xxx
```

we simply type:

```
google.com
```

Example DNS Server:

```
8.8.8.8
```

---

# Security Perspective

Understanding communication principles is essential in cybersecurity.

As a future SOC Analyst, I need to understand:

- How devices communicate
- Which protocols are being used
- Where communication can fail
- How attackers exploit insecure protocols
- How network traffic moves through different layers

Without strong networking fundamentals, analyzing network attacks becomes much more difficult.

---

# Key Terms

- Protocol
- Standard
- TCP/IP
- OSI
- IPv4
- IPv6
- MAC Address
- Default Gateway
- DNS
- HTTP
- HTTPS
- DHCP
- FTP
- SSH

---

# What I Learned

After completing this module, I can:

- Explain the purpose of communication protocols.
- Understand why networking standards are important.
- Compare the OSI and TCP/IP models.
- Identify IPv4, IPv6, MAC addresses, DNS, and Default Gateway.
- Explain how devices communicate across a network.
- Understand why networking knowledge is important for cybersecurity.

---

## Reflection

This module helped me understand what actually happens when one device communicates with another. Instead of only seeing IP addresses and protocols, I now understand their purpose and how they work together. These concepts will be useful when I start analyzing network traffic, investigating incidents, and working with packet analysis tools like Wireshark.

---
