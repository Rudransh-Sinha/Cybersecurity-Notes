# Module 11 - Dynamic Addressing with DHCP


---

## Module Overview

In this module, I learned how devices can automatically get their IP configuration using **DHCP (Dynamic Host Configuration Protocol)** instead of configuring every device manually.

DHCP makes network management easier, especially when there are many devices connected to a network.



---

## What is DHCP?

**DHCP** is a network protocol used to automatically provide devices with their network configuration.

A DHCP server can provide:

* IP address
* Subnet mask
* Default gateway
* DNS server address
* Lease information

This means the administrator does not need to manually configure these settings on every device.

---

## Why DHCP is Needed

Without DHCP, every device would need to be configured manually.

For example:

```text
PC 1 → Manual IP
PC 2 → Manual IP
PC 3 → Manual IP
PC 4 → Manual IP
...
```


This becomes difficult to manage and can also cause problems such as duplicate IP addresses.

With DHCP:

```text
Device → DHCP Server → IP Configuration
```

The configuration is provided automatically.

---

## DHCP DORA Process

The main DHCP process is known as **DORA**.

### 1. DHCP Discover

The client broadcasts a **DHCP Discover** message to find available DHCP servers.

```text
Client → DHCP Discover → Broadcast
```

### 2. DHCP Offer

A DHCP server responds with a **DHCP Offer** containing an available IP configuration.

```text
DHCP Server → DHCP Offer → Client
```

### 3. DHCP Request

The client sends a **DHCP Request** to request the offered configuration.

```text
Client → DHCP Request → Server
```

### 4. DHCP Acknowledgment

The server sends a **DHCP ACK** confirming that the client can use the assigned configuration.

```text
DHCP Server → DHCP ACK → Client
```

So the complete process is:

```text
Discover → Offer → Request → Acknowledgment
```

**DORA = Discover, Offer, Request, Acknowledgment**

---

## DHCP Lease

The IP address provided by DHCP is normally not permanent.

It is assigned for a specific period called a **lease**.

When the lease is close to expiring, the client can request to renew it.

This allows DHCP to reuse addresses when devices leave the network.

---

## DHCP and Broadcasts

When a device does not yet have an IP address, it uses broadcast communication to find a DHCP server on the local network.

This is why DHCP is closely related to the concept of **broadcast domains** that I learned in the previous modules.

---

## DHCP Benefits

DHCP provides several advantages:

* Automatic IP configuration
* Reduces manual configuration
* Prevents many IP configuration mistakes
* Helps avoid duplicate IP addresses
* Makes network administration easier
* Allows IP addresses to be reused
* Works well for large networks

---

## DHCP vs Static Addressing

| DHCP                           | Static                                |
| ------------------------------ | ------------------------------------- |
| Configuration is automatic     | Configuration is manual               |
| IP can change                  | IP normally stays fixed               |
| Easier for large networks      | More administrative work              |
| Good for normal client devices | Useful for servers and infrastructure |

---

## Key Terms

* DHCP
* DHCP Server
* DHCP Client
* DHCP Lease
* DHCP Discover
* DHCP Offer
* DHCP Request
* DHCP ACK
* DORA
* Default Gateway
* DNS Server
* Dynamic Addressing
* Static Addressing

---

## Key Takeaways

* DHCP automatically provides network configuration to clients.
* DHCP can provide an IP address, subnet mask, default gateway and DNS information.
* The DHCP process follows **DORA**.
* DHCP uses broadcasts when a client is looking for a DHCP server.
* IP addresses are usually assigned for a specific lease period.
* DHCP makes managing networks much easier compared to manually configuring every device.

---


## Reflection

This module helped me understand what actually happens when a device joins a network and gets an IP address automatically. The **DORA process** is especially important because it explains the basic communication between a DHCP client and server.





 
