# Module 10 - IPv6 Addressing Formats and Rules

**Course:** Cisco Networking Academy – Networking Basics  
**Module:** 10 - IPv6 Addressing Formats and Rules

---

# Module Overview

In this module, I learned why IPv6 was introduced, how IPv6 addresses are written, and the rules used to simplify long IPv6 addresses. I also learned how IPv6 communicates with IPv4 networks during the transition period.

---

# Why IPv6?

IPv4 has a limited number of addresses, which is not enough for the growing number of internet-connected devices.

IPv6 solves this problem by providing:

- 128-bit addressing
- A huge address space
- Better scalability
- Improved routing efficiency
- Better support for future networking

---

# IPv6 Address Format

IPv6 addresses are:

- 128 bits long
- Written in hexadecimal format
- Made up of 8 groups (hextets)
- Each group contains 4 hexadecimal digits
- Total of 32 hexadecimal characters
- Not case-sensitive

Example:

```
2001:0db8:0000:0000:0000:ff00:0042:8329
```

---

# IPv6 Address Simplification Rules

Because IPv6 addresses are long, two rules are used to shorten them.

## Rule 1 - Omit Leading Zeroes

Leading zeroes in a hextet can be removed.

Example:

```
01ab → 1ab
000f → f
0000 → 0
```

---

## Rule 2 - Double Colon (::)

A double colon (::) can replace one or more consecutive groups containing only zeroes.

Example:

```
2001:0db8:0000:0000:0000:ff00:0042:8329

↓

2001:db8::ff00:42:8329
```

Important Notes:

- `::` can be used **only once** in a single IPv6 address.
- If there are multiple groups of zeroes, use `::` for the **longest sequence**.
- If two zero sequences have the same length, use the **first sequence**.

---

# IPv4 to IPv6 Transition

Since IPv4 and IPv6 are both used today, different transition methods help them communicate.

## Tunneling

Tunneling is the process of transporting **IPv6 packets over an IPv4 network**.

It allows IPv6 communication even when the underlying infrastructure is still IPv4.

---

## NAT64

NAT64 is a translation technology that enables:

- IPv6-only devices
- to communicate with
- IPv4-only devices

It translates IPv6 traffic into IPv4 traffic and vice versa.

---

# Key Terms Learned

- IPv6
- Hexadecimal
- Hextet
- Leading Zero
- Double Colon (::)
- 128-bit Address
- Tunneling
- NAT64
- IPv4 Transition

---

# Key Takeaways

- IPv6 was introduced to overcome IPv4 address exhaustion.
- IPv6 addresses are 128 bits long and written in hexadecimal.
- IPv6 addresses are not case-sensitive.
- Leading zeroes can be omitted to shorten addresses.
- Double colon (::) replaces consecutive zero groups and can only be used once per address.
- Tunneling allows IPv6 packets to travel across IPv4 networks.
- NAT64 enables communication between IPv6-only and IPv4-only devices.

---

# Reflection

This module helped me understand the structure of IPv6 addresses and the rules used to simplify them. I also learned how technologies like Tunneling and NAT64 make the transition from IPv4 to IPv6 possible. These concepts are important for modern networking and cybersecurity because IPv6 adoption continues to grow across enterprise environments.

---

