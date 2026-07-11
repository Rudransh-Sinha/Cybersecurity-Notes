# TryHackMe Write-up: What is Networking?

**Platform:** TryHackMe  
**Room:** What is Networking?  
**Completed On:** 11 July 2026  
**Difficulty:** Beginner

---

## Objective

This room introduced the basic concepts of computer networking and explained how devices communicate with each other over a network. As someone starting my cybersecurity journey, this gave me a solid foundation for understanding future networking and security topics.

---

## What I Learned

### 1. What is a Network?

A network is simply a group of devices connected together so they can communicate and share data. These devices can include computers, phones, servers, printers, and many other smart devices.

---

### 2. What is the Internet?

The Internet is a massive network made up of millions of smaller networks connected together. Whenever I open a website or use an online service, my device communicates with servers over the Internet.

---

### 3. IP Address vs MAC Address

One of the biggest takeaways from this room was understanding the difference between IP and MAC addresses.

- **IP Address:** Used to identify a device on a network and helps route data to the correct destination.
    
- **MAC Address:** A unique hardware address assigned to a network interface that identifies the physical device on a local network.
    

I learned that IP addresses can change depending on the network, while MAC addresses are tied to the hardware.

---

### 4. Public and Private IP Addresses

I understood the difference between:

- **Private IP Addresses** – Used inside local networks such as home or office Wi-Fi.
    
- **Public IP Addresses** – Assigned by an Internet Service Provider (ISP) and used for communication over the Internet.
    

---

### 5. Ping (ICMP)

This room introduced the **ping** command.

I learned that ping uses the **ICMP (Internet Control Message Protocol)** to check whether another device is reachable and to measure the response time between two devices.

Example:

```bash
ping 8.8.8.8
```

Ping is useful for:

- Checking network connectivity
    
- Troubleshooting connection issues
    
- Measuring response time (latency)
    

---

## Key Terms Learned

- Network
    
- Internet
    
- IP Address
    
- MAC Address
    
- Public IP
    
- Private IP
    
- ICMP
    
- Ping
    

---

## Key Takeaways

- Networking is one of the most important foundations of cybersecurity.
    
- Every device on a network needs an IP address for communication.
    
- MAC addresses uniquely identify hardware on a local network.
    
- The Internet is made up of many interconnected networks.
    
- Ping is a simple but powerful tool for testing network connectivity.
    

---

## Reflection

This room helped me understand concepts that I had heard many times but never fully understood. Instead of memorizing definitions, I now have a much clearer idea of how devices communicate across networks. This knowledge will make learning topics like packet analysis, Wireshark, Nmap, and network security much easier in the coming weeks.

---
