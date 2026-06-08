# 🌐 Cybersecurity Internship Task 02 Report

**Date:** June 4, 2026

**Intern:** Nehaa J

---

## 🔍 Task Objectives

* Understand common network devices and their functions
* Learn IP addressing and classify IP addresses as Public or Private
* Analyze network settings on a local device
* Understand how DNS and network communication work
* Practice basic networking commands

---

## ✅ Part A: Network Devices Research

### Router

**Purpose:** Connects different networks and routes data between them.

**How it Works:** Uses IP addresses to determine the best path for data packets.

**Real-World Usage:** Home Wi-Fi routers connect devices to the internet.

### Switch

**Purpose:** Connects devices within the same network.

**How it Works:** Uses MAC addresses to forward data only to the intended device.

**Real-World Usage:** Office LAN environments.

### Hub

**Purpose:** Connects multiple devices in a network.

**How it Works:** Broadcasts incoming data to all connected devices.

**Real-World Usage:** Older small-scale networks.

### Access Point

**Purpose:** Provides wireless network access.

**How it Works:** Connects wireless devices to a wired network.

**Real-World Usage:** Wi-Fi networks in homes, schools, and offices.

### Firewall

**Purpose:** Protects networks from unauthorized access.

**How it Works:** Filters incoming and outgoing network traffic.

**Real-World Usage:** Personal computers and enterprise networks.

### Modem

**Purpose:** Connects a network to the Internet Service Provider (ISP).

**How it Works:** Converts digital signals for internet communication.

**Real-World Usage:** Broadband internet connections.

---

## ✅ Part B: IP Address Classification

| IP Address    | Category |
| ------------- | -------- |
| 192.168.1.10  | Private  |
| 10.0.0.5      | Private  |
| 172.16.5.20   | Private  |
| 8.8.8.8       | Public   |
| 1.1.1.1       | Public   |
| 192.168.100.1 | Private  |

### Explanation

* 10.0.0.0 – 10.255.255.255 → Private Range
* 172.16.0.0 – 172.31.255.255 → Private Range
* 192.168.0.0 – 192.168.255.255 → Private Range
* Public IPs are globally routable on the internet.

---

## ✅ Part C: Understanding My Network

### Network Information

| Parameter       | Value                  |
| --------------- | ---------------------- |
| IPv4 Address    | (Your IPv4 Address)    |
| Default Gateway | (Your Gateway Address) |
| DNS Server      | (Your DNS Server)      |

### Answers

**Which IP range does your device belong to?**

My device belongs to the private IP address range.

**Is it Public or Private?**

Private IP Address.

**What role does your router play in your network?**

The router acts as a gateway between the local network and the internet, forwarding data packets between devices and external networks.

**What would happen if the DNS server stopped working?**

Domain names such as google.com would not resolve into IP addresses, making websites inaccessible by name.

---

## ✅ Part D: Network Communication Flow

### Communication Diagram

Your Device
⬇
Router
⬇
DNS Server
⬇
Google Server
⬇
Response Back to Device

### Explanation

1. The user enters [www.google.com](http://www.google.com) in the browser.
2. The router forwards the request to a DNS server.
3. The DNS server resolves the domain name into an IP address.
4. The request is sent to Google's server.
5. Google returns the requested webpage to the device.

---

## ✅ Part E: Practical Command Exercise

### Commands Executed

#### Windows

```cmd
ipconfig /all
nslookup google.com
ping google.com
```

#### Linux

```bash
ip addr
nslookup google.com
ping google.com
```

### Results

**What IP address did DNS return for Google?**

(Insert your nslookup result)

**Was the ping successful?**

Yes, the ping was successful.

**Why is DNS important before communication begins?**

DNS translates human-readable domain names into IP addresses, enabling devices to locate servers on the internet.

---

## 📸 Screenshot Evidence

✅ ipconfig /all output

✅ nslookup google.com output

✅ ping google.com output

✅ Network Communication Diagram

All screenshots are included in the repository under `/Screenshots/`.

---

## 🎯 Learning Outcome

This task improved my understanding of networking fundamentals, including network devices, IP addressing, DNS resolution, and how data travels across networks. It also provided hands-on experience with basic networking commands and network troubleshooting concepts.
