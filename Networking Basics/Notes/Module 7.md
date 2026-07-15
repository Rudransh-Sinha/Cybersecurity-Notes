# Module 7: The Access Layer

## Overview
The Access Layer is where end devices like PCs, laptops, printers, and IP phones connect to the network. It is the first point of communication in a LAN and mainly uses Ethernet technology for wired communication.

---

# 1. Encapsulation

Encapsulation is the process of adding protocol information to data before transmission.

As data moves down the networking stack, each layer adds its own header (and sometimes a trailer), preparing it for transmission.

### Data Flow

Application Data
↓
Segment (Transport Layer)
↓
Packet (Network Layer)
↓
Frame (Data Link Layer)
↓
Bits (Physical Layer)

At the receiving end, this process is reversed, known as **De-encapsulation**.

### Key Points

- Data is wrapped with protocol information at every layer.
- Ensures proper delivery across the network.
- The receiver removes headers layer by layer.

---

# 2. Ethernet Frame

An Ethernet Frame is the Data Link Layer unit used for communication over Ethernet networks.

## Main Components

| Field | Purpose |
|--------|---------|
| Preamble | Synchronizes sender and receiver |
| Start Frame Delimiter (SFD) | Marks the beginning of the frame |
| Destination MAC | Receiver's MAC Address |
| Source MAC | Sender's MAC Address |
| Type/Length | Identifies the protocol |
| Data | Actual payload |
| Frame Check Sequence (FCS) | Detects transmission errors |

---

# 3. MAC Address

A MAC (Media Access Control) Address is the physical address assigned to every network interface card (NIC).

### Example

```
00:1A:2B:3C:4D:5E
```

### Characteristics

- 48-bit unique identifier
- Assigned by the manufacturer
- Works at Layer 2 (Data Link Layer)
- Used for communication within the same LAN

---

# 4. The Access Layer

The Access Layer connects end devices to the network.

Examples:

- Computers
- Laptops
- Printers
- IP Phones
- Wireless Access Points

Its main responsibility is providing users access to network resources.

---

# 5. Ethernet Hub

A Hub is a basic networking device that broadcasts incoming data to every connected device.

### Characteristics

- Layer 1 device
- No MAC address learning
- Broadcasts frames to all ports
- Half-duplex communication
- High collision rate
- Mostly obsolete today

---

# 6. Ethernet Switch

A Switch is a Layer 2 device that intelligently forwards frames only to the correct destination.

Instead of sending data everywhere, it uses MAC addresses to determine the correct port.

### Advantages

- Learns MAC addresses automatically
- Sends frames only where needed
- Reduces collisions
- Supports Full Duplex communication
- Faster and more efficient than hubs

---

# 7. MAC Address Table

A Switch maintains a MAC Address Table containing:

- MAC Address
- Connected Port

Whenever a device sends a frame, the switch learns the source MAC address and stores it.

### Example

| MAC Address | Port |
|--------------|------|
| AA:BB:CC:11:22:33 | Fa0/1 |
| DD:EE:FF:44:55:66 | Fa0/2 |

---

# 8. Hub vs Switch

| Feature | Hub | Switch |
|---------|------|---------|
| OSI Layer | Layer 1 | Layer 2 |
| Data Forwarding | Broadcasts to all ports | Sends to specific destination |
| MAC Address Table | No | Yes |
| Collision Domain | Shared | Separate for each port |
| Performance | Slower | Faster |
| Duplex | Half Duplex | Full Duplex |

---

# Key Takeaways

- Encapsulation prepares data for transmission.
- Ethernet Frames carry data across wired networks.
- MAC Addresses uniquely identify devices inside a LAN.
- The Access Layer connects users to the network.
- Hubs broadcast data and create collisions.
- Switches learn MAC addresses and forward frames intelligently.
- MAC Address Tables improve network efficiency and reduce unnecessary traffic.

---

# Interview Questions

### Q1. What is encapsulation?
**Answer:** Encapsulation is the process of adding protocol headers (and trailers) to data as it moves down the OSI model before transmission.

### Q2. What is an Ethernet Frame?
**Answer:** It is the Layer 2 data unit that carries data over Ethernet networks.

### Q3. What is a MAC Address?
**Answer:** A unique 48-bit hardware address assigned to every network interface card.

### Q4. Why are switches preferred over hubs?
**Answer:** Switches use MAC Address Tables to forward frames only to the intended device, reducing collisions and improving network performance.

### Q5. At which OSI layer does a switch operate?
**Answer:** Layer 2 (Data Link Layer).

---

## What I Learned

- Understood how data is encapsulated before transmission.
- Learned the structure of an Ethernet Frame.
- Explored the purpose of MAC Addresses.
- Studied the role of the Access Layer in a LAN.
