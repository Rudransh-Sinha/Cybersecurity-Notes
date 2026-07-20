# Module 9.1 - IPv4 Unicast, Broadcast & Multicast

**Course:** Cisco Networking Academy - Networking Basics  
**Module:** IPv4 and Network Segmentation  
**Section Completed:** 9.1

---

# What I Learned

## IPv4 Communication Types

An IPv4 packet can be sent in three different ways depending on the destination.

- Unicast
- Broadcast
- Multicast

Each type is used for a different purpose in a network.

---

## 1. Unicast

Unicast is **one-to-one communication**.

One device sends data directly to one specific device using its unique IPv4 address.

Examples:

- Opening a website
- SSH connection
- Sending an email
- Downloading a file

Most internet communication uses Unicast.

---

## 2. Broadcast

Broadcast is **one-to-all communication** inside the same network.

The sender sends one packet, and every device in the local network receives it.

Important points:

- Broadcast traffic never crosses a router.
- Mainly used for device discovery and network services.

Example:

A device asking,

> "Who has this IP address?"

using ARP.

---

## 3. Multicast

Multicast is **one-to-many communication**.

Instead of sending data to every device, packets are delivered only to devices that joined a specific multicast group.

This saves bandwidth compared to broadcast.

Examples:

- Live video streaming
- Online meetings
- IPTV
- Real-time media

---

## Difference Between Them

| Type | Communication | Receivers |
|------|---------------|-----------|
| Unicast | One → One | Single device |
| Broadcast | One → All | Every device in the LAN |
| Multicast | One → Many | Only subscribed devices |

---

# Key Terms Learned

- IPv4
- Unicast
- Broadcast
- Multicast
- Broadcast Domain
- Multicast Group

---

# Key Takeaways

- Unicast is the most common communication method.
- Broadcast reaches every device inside the local network.
- Routers do not forward broadcast traffic.
- Multicast delivers data only to interested devices.
- Choosing the correct communication type improves network efficiency.

---

# Reflection

This section made it clear that not every packet is sent the same way. Understanding the difference between Unicast, Broadcast, and Multicast helps explain how networks reduce unnecessary traffic and improve communication efficiency. These concepts are also important while analyzing network traffic in cybersecurity.