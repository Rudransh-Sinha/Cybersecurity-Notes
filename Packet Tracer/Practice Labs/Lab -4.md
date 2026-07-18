# Packet Tracer Lab 4: Connect to a Web Server

## Objective

The objective of this lab was to understand how a client device communicates with a web server over a network using HTTP. This exercise demonstrates the basic client-server model and verifies successful connectivity by accessing a webpage through the server's IP address.

---

## Lab Scenario

A PC is connected to the Internet and needs to access a remote web server hosting a website.

The goal is to establish HTTP communication and verify that the client can successfully load the webpage.

---

## Network Topology

```
PC0 (192.168.1.100)
        │
     Internet
        │
LearnIP Web Server
172.33.100.50
```

---

## Devices Used

| Device             | Role               |
| ------------------ | ------------------ |
| PC0                | Client Computer    |
| Internet Cloud     | Simulated Internet |
| LearnIP Web Server | Web Server         |

---

## IP Addressing

| Device             | IP Address    |
| ------------------ | ------------- |
| PC0                | 192.168.1.100 |
| LearnIP Web Server | 172.33.100.50 |

---

## Steps Performed

1. Opened the Packet Tracer activity.
2. Verified the network topology.
3. Opened **PC0 → Desktop → Web Browser**.
4. Entered the web server IP address:

```
http://172.33.100.50
```

5. Clicked **Go**.
6. Confirmed that the webpage loaded successfully.

---

## Output

The browser displayed the following message:

> **Welcome to the Learn IP Web Site**

This confirms that HTTP communication between the client and the web server was successful.

---

## Networking Concepts Learned

- Client-Server Architecture
- HTTP (HyperText Transfer Protocol)
- Web Browser Communication
- IP Address-Based Access
- End-to-End Network Connectivity
- Basic Packet Tracer Navigation

---

## Key Observations

- The client uses the web browser to send an HTTP request.
- The request is forwarded through the simulated Internet.
- The web server processes the request and returns the webpage.
- Successful page loading indicates proper network connectivity.

---

## Skills Gained

- Using the Packet Tracer Web Browser
- Understanding HTTP communication
- Identifying server IP addresses
- Verifying network connectivity
- Observing client-server interactions

---

## Screenshot

## ![Lab-4 Completed](<Lab-4 Done.png>)

## Conclusion

This lab introduced the fundamentals of web communication in a network environment. By accessing a remote web server through its IP address, I gained a practical understanding of how HTTP enables communication between clients and servers, reinforcing core networking concepts essential for cybersecurity.
