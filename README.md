# NETWORKWALKS-B083-WK2-CYBERSECURITY-FOOTPRINTING-NETWORK-SCANNING
# 🔐 Week 2 — Footprinting & Network Scanning

**Cybersecurity & Ethical Hacking Learning Program | Networkwalks**

This repository contains my Week 2 practical work from the Cybersecurity & Ethical Hacking learning program at Networkwalks.

The week focused on two main areas:

* **Footprinting & Reconnaissance** using Kali Linux
* **Network Scanning & Discovery** using Zenmap on my own local network

The main goal of these activities was to understand how information can be collected about a target and how active devices can be identified and mapped within a network.

---

## 📌 Activities Completed

### 1. Footprinting & Reconnaissance

For the footprinting activity, I performed reconnaissance on the `networkwalks.com` domain using six Kali Linux tools.

| Tool     | Purpose                                                 |
| -------- | ------------------------------------------------------- |
| WHOIS    | Collect domain registration and name server information |
| WhatWeb  | Identify web technologies and software                  |
| Nslookup | Resolve domain names to IP addresses                    |
| Curl     | Inspect HTTP response headers                           |
| Wafw00f  | Identify the Web Application Firewall                   |
| DNSRecon | Collect and enumerate DNS information                   |

These tools helped me understand how different reconnaissance tools provide different types of information about the same target.

---

### 2. Network Scanning with Zenmap

For the second activity, I used **Zenmap (Nmap GUI)** to scan my own local network.

I first used Windows `ipconfig` to identify my local IP address and subnet.

**Local IP:** `10.0.0.10`
**Subnet:** `10.0.0.0/24`

I then performed a Ping Scan using:

```bash
nmap -sn 10.0.0.0/24
```

The scan identified four live hosts:

* `10.0.0.1`
* `10.0.0.2`
* `10.0.0.3`
* `10.0.0.10`

I also collected available MAC address information and generated a network topology using Zenmap.

During the scan, I observed that `10.0.0.1` and `10.0.0.2` returned the same MAC address. I documented this as an observation requiring investigation rather than treating it as a confirmed vulnerability.

---

## 🛠️ Tools & Technologies

* Kali Linux
* Windows 10
* Zenmap
* Nmap
* WHOIS
* WhatWeb
* Nslookup
* Curl
* Wafw00f
* DNSRecon
* Windows CMD

---

## 📚 What I Learned

Through these practicals, I learned:

* How different reconnaissance tools collect different types of information
* How domain and DNS information can be gathered
* How web technologies and HTTP headers can be identified
* How a WAF can be detected during reconnaissance
* How to identify my local network and subnet
* How to discover active hosts using Nmap
* How IP and MAC addresses can be observed during network discovery
* How to create a basic network topology
* Why unusual scan results should be investigated and documented
* The importance of performing reconnaissance and scanning only within an authorized scope

---

## 🔒 Scope & Authorization

The footprinting activity was performed as part of an assigned educational cybersecurity practical with the required permission.

The network scanning activity was performed on my own local network and devices.

No exploitation or unauthorized access was performed as part of these activities.

These practicals were completed for educational purposes to understand reconnaissance, information gathering, and network discovery.

---

## 📄 Full Report

The complete report contains the detailed methodology, commands, observations, evidence, risk analysis, recommendations, and conclusion from the Week 2 activities.

📁 **[View the complete report](Report/W2-PM-FINAL-Rushda-Khan.pdf)**

---

## 👤 Author

**Rushda Khan**

Cybersecurity & Ethical Hacking Learning Program
**Networkwalks | Batch B083**

**Week 02 — Footprinting & Network Scanning**

---

> ⚠️ All security testing documented in this repository was performed within an authorized educational scope or on systems and networks owned by me.

