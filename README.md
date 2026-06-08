# 🌐 Networking Task 02 Report

**Date:** June 8, 2026

**Intern:** Nehaa J

---

## 🔍 Task Objectives

* Understand common network devices and their functions
* Learn IP addressing concepts and classifications
* Understand network communication flow
* Perform practical networking commands
* Analyze DNS and network connectivity

---

## ✅ Part A: Network Devices Research

### Router

**Purpose:** Connects different networks and directs data traffic.

**How it Works:** Uses IP addresses to determine the best path for data packets.

**Real-World Usage:** Home and office internet routers.

### Switch

**Purpose:** Connects devices within the same network.

**How it Works:** Uses MAC addresses to send data only to the intended device.

**Real-World Usage:** Office LAN networks.

### Hub

**Purpose:** Connects multiple devices in a network.

**How it Works:** Broadcasts incoming data to all connected devices.

**Real-World Usage:** Older network environments.

### Access Point

**Purpose:** Provides wireless connectivity to devices.

**How it Works:** Extends a wired network through Wi-Fi signals.

**Real-World Usage:** Homes, schools, and offices.

### Firewall

**Purpose:** Protects a network from unauthorized access.

**How it Works:** Monitors and filters incoming and outgoing traffic.

**Real-World Usage:** Enterprise networks and personal computers.

### Modem

**Purpose:** Connects a network to an Internet Service Provider (ISP).

**How it Works:** Converts signals between the ISP and local devices.

**Real-World Usage:** Broadband internet connections.

---

## ✅ Part B: IP Address Classification

| IP Address    | Classification | Reason                                        |
| ------------- | -------------- | --------------------------------------------- |
| 192.168.1.10  | Private        | Reserved private IP range (192.168.x.x)       |
| 10.0.0.5      | Private        | Reserved private IP range (10.x.x.x)          |
| 172.16.5.20   | Private        | Reserved private IP range (172.16–172.31.x.x) |
| 8.8.8.8       | Public         | Google's public DNS server                    |
| 1.1.1.1       | Public         | Cloudflare's public DNS server                |
| 192.168.100.1 | Private        | Reserved private IP range (192.168.x.x)       |

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

The router acts as the gateway between my local network and the internet. It forwards data packets between devices and external servers.

**What would happen if the DNS server stopped working?**

Websites could not be accessed using domain names because the system would be unable to translate domain names into IP addresses.

---

## ✅ Part D: Network Communication Flow

### Network Communication Diagram

```text
Your Device
      ↓
    Router
      ↓
  DNS Server
      ↓
 Google Server
      ↓
Response Back to Device
```

### Communication Process

**Step 1:** The user enters [www.google.com](http://www.google.com) in the browser.

**Step 2:** The router forwards the request to a DNS server.

**Step 3:** The DNS server translates the domain name into an IP address.

**Step 4:** The request is sent to Google's server using the resolved IP address.

**Step 5:** Google processes the request and sends the webpage data back to the user's device.

---

## ✅ Part E: Practical Command Exercise

### Commands Used

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

(Insert the IP address from your nslookup result.)

**Was the ping successful?**

Yes, the ping was successful and replies were received from Google's server.

**Why is DNS important before communication begins?**

DNS converts human-readable domain names into IP addresses, allowing devices to locate and communicate with servers on the internet.

---

## 📸 Screenshot Evidence

✅ ipconfig /all output
<img width="1536" height="1024" alt="ipconfig" src="https://github.com/user-attachments/assets/982e886a-c7af-47c6-891a-5135850ce948" />


✅ nslookup google.com output
<img width="1445" height="1088" alt="nslookup" src="https://github.com/user-attachments/assets/8c1e468b-fdfe-4931-becf-70537d023f4d" />

✅ ping google.com output
<img width="1536" height="1024" alt="ping" src="https://github.com/user-attachments/assets/2a4ad5d4-254f-4c57-8270-f924f90bc121" />


✅ Network Communication Diagram

All screenshots are included in the repository under `/Screenshots/`.

---

## 🎯 Learning Outcome

Through this task, I learned about network devices, IP address classifications, DNS resolution, and how data travels through a network. I also gained practical experience using networking commands to analyze connectivity and network configurations.
