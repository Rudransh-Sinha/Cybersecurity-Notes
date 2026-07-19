# TryHackMe Write-up: Intro to Networking

**Platform:** TryHackMe  
**Room:** Intro to Networking  
**Difficulty:** Easy  
**Status:** Completed  
**Learning Category:** Networking Fundamentals

---

# Objective

This room introduced me to how computer networks work, why they are important, and how devices communicate with each other. It also helped me understand some core networking concepts that are the foundation of cybersecurity.

---

# What I Learned

## What is a Network?

A network is simply a group of devices connected together so they can exchange data.

Examples:
- Home Wi-Fi
- Office Network
- Internet (largest network)

Without networking, cybersecurity wouldn't exist because every attack and every defense happens through networks.

---

## Types of Networks

### LAN (Local Area Network)

- Covers a small area
- Faster communication
- Used in homes, schools, and offices

Example:
A home Wi-Fi where my laptop and phone are connected.

---

### WAN (Wide Area Network)

- Connects multiple LANs
- Covers large geographical areas
- Internet is the biggest WAN

---

## Network Devices

### Router

- Connects different networks
- Sends traffic to the correct destination
- Usually acts as the default gateway

---

### Switch

- Connects devices inside the same LAN
- Sends data only to the intended device
- More efficient than a hub

---

### Access Point (AP)

- Provides wireless connectivity
- Allows Wi-Fi devices to join the network

---

## IP Address

Every device connected to a network needs a unique IP address.

Think of it as the home address of a device.

Example:

```
192.168.1.10
```

No two devices on the same network should have the same IP address.

---

## Public vs Private IP

### Private IP

Used inside local networks.

Examples:

- 192.168.x.x
- 10.x.x.x
- 172.16.x.x – 172.31.x.x

Cannot be accessed directly from the internet.

---

### Public IP

Assigned by the ISP.
Visible on the internet and used for communication outside the local network.

---

## MAC Address

Every network interface has a unique MAC Address.

- Physical hardware address
- Used for communication inside a LAN
- Does not normally change

---

## DNS

DNS converts domain names into IP addresses.

Instead of remembering:

```
142.250.xxx.xxx
```

We simply type:

```
google.com
```

DNS finds the correct IP for us.

---

## Ports

Ports allow multiple network services to run on a single device.

Examples:

- 22 → SSH
- 80 → HTTP
- 443 → HTTPS
- 53 → DNS

Understanding ports is extremely important in penetration testing and network security.

---

# Key Terms Learned

- LAN
- WAN
- Router
- Switch
- Access Point
- IP Address
- Public IP
- Private IP
- MAC Address
- DNS
- Ports

---

# Key Takeaways

- Networking is one of the strongest foundations of cybersecurity.
- Every connected device has an IP address and a MAC address.
- Routers connect networks while switches connect devices within the same network.
- DNS makes the internet easier by translating names into IP addresses.
- Ports identify different services running on a system.

---

# Reflection

This room strengthened my understanding of networking basics before moving into more advanced cybersecurity topics. Instead of just memorizing definitions, I now have a clearer idea of how devices communicate and why networking knowledge is essential for SOC analysis, penetration testing, and threat investigation.

This room gave me a stronger foundation for the upcoming networking and security labs on my cybersecurity journey.
