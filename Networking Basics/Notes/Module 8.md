# Module 8 - The Internet Protocol (IPv4)

## Overview

In this module, I learned how IPv4 addressing works and why every device connected to a network requires a unique IP address. I also explored the structure of an IPv4 address, network and host portions, subnet masks, and how routers use IP addresses to deliver data to the correct destination.

This module is one of the most important networking fundamentals because IP addressing is the backbone of network communication.

---

# What is an IPv4 Address?

An IPv4 address is a **logical address** assigned to a device on a network.

Its primary purpose is to:

- Identify a device uniquely.
- Allow communication between devices.
- Help routers deliver data to the correct destination.

Without an IP address, a device cannot communicate over a TCP/IP network.

Example:

```
192.168.1.10
```

---

# Why is an IPv4 Address Important?

Every packet sent across a network contains:

- Source IP Address
- Destination IP Address

Networking devices use this information to forward packets to the correct destination and return responses to the sender.

Every IPv4 address must be unique within its network.

---

# IPv4 Address Structure

An IPv4 address consists of **32 bits**, divided into **4 octets**.

Example:

```
192.168.5.11
```

Each octet contains **8 bits**.

```
192 . 168 . 5 . 11
```

---

# Network Portion and Host Portion

An IPv4 address has two parts:

## Network Portion

Identifies the network where the device belongs.

## Host Portion

Identifies the individual device within that network.

Example:

```
IP Address : 192.168.5.11
Subnet Mask: 255.255.255.0
```

Network ID:

```
192.168.5
```

Host ID:

```
11
```

This is known as **hierarchical addressing** because the address is divided into a network part and a host part.

---

# Subnet Mask

A subnet mask tells the device which part of an IP address represents:

- Network
- Host

Example:

```
255.255.255.0
```

This means:

- First three octets → Network
- Last octet → Host

---

# Hierarchical Addressing

Routers mainly use the **network portion** of an IP address.

They don't need to know every individual device.

Instead, they simply determine:

> Which network should this packet be sent to?

This makes routing faster and more efficient.

---

# Public vs Private IPv4 Addresses

## Private IPv4 Address

Used inside local networks.

Cannot be accessed directly from the Internet.

Examples:

```
192.168.x.x
172.16.x.x – 172.31.x.x
10.x.x.x
```

---

## Public IPv4 Address

Assigned by an Internet Service Provider (ISP).

Allows communication over the Internet.

Public IP addresses are globally unique.

---

# Why IPv4 Needs to be Conserved

IPv4 provides approximately **4.3 billion** unique addresses.

Because the number of internet-connected devices has grown rapidly, IPv4 addresses are limited.

This is one of the reasons why IPv6 was introduced.

---

# Security Perspective

As a cybersecurity learner, I realized that understanding IPv4 addressing is essential for:

- Reading network logs.
- Investigating suspicious traffic.
- Identifying source and destination systems.
- Configuring firewalls and access control rules.
- Performing network troubleshooting.

Almost every SOC investigation starts with analyzing IP addresses.

---

# Key Terms

- IPv4
- Logical Address
- Network ID
- Host ID
- Subnet Mask
- Hierarchical Addressing
- Public IP
- Private IP
- Router
- Packet
- Source IP
- Destination IP

---

# What I Learned

After completing this module, I can:

- Explain the purpose of an IPv4 address.
- Describe the structure of an IPv4 address.
- Differentiate between the network and host portions.
- Understand the role of subnet masks.
- Explain hierarchical addressing.
- Differentiate between public and private IPv4 addresses.
- Understand how routers forward packets using IP addresses.

---

## Reflection

This module helped me understand what an IP address actually represents instead of simply memorizing numbers. I now know how devices are identified on a network, how routers make forwarding decisions, and why IP addressing is one of the most important concepts in networking. These fundamentals will be extremely useful when analyzing network traffic and investigating security incidents.

---
