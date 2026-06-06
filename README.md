# Wireshark Attack Library

A collection of packet captures and protocol analysis reports demonstrating common network activities and simulated attack scenarios using Wireshark.

---

## Overview

This project was created to study how different protocols and attack-related behaviors appear at the packet level.

Each scenario includes:

* Packet capture files (`.pcapng`)
* Screenshots from Wireshark
* Detailed analysis reports

---

## Scenarios Covered

### ICMP Traffic Analysis

* Echo Requests
* Echo Replies
* Connectivity verification

### DNS Traffic Analysis

* DNS queries
* DNS responses
* Domain resolution behavior

### HTTP Traffic Analysis

* HTTP GET requests
* HTTP 200 OK responses
* HTML content transfer

### TCP SYN Port Scan Analysis

* Three-way handshake
* Open port identification
* Reconnaissance behavior

### Reverse Shell Simulation

* Netcat listener and client communication
* Data exchange over TCP
* Session establishment and termination

---

## Tools Used

* Wireshark
* Nmap
* Netcat
* Python HTTP Server
* dig
* Ping Utility

---

## Repository Structure

```text
Wireshark-Attack-Library/
│
├── docs/
├── pcaps/
├── screenshots/
├── LICENSE
└── README.md
```

---

## Skills Demonstrated

* Packet Analysis
* TCP/IP Fundamentals
* Protocol Inspection
* Network Reconnaissance
* Traffic Analysis
* HTTP Analysis
* DNS Analysis
* ICMP Analysis
* Reverse Shell Traffic Identification

---

## Capture Files

| Scenario                 | PCAP File                         |
| ------------------------ | --------------------------------- |
| ICMP Traffic             | `icmp_ping.pcapng`                |
| DNS Traffic              | `dns_traffic.pcapng`              |
| HTTP Traffic             | `http_traffic.pcapng`             |
| Port Scan                | `port_scan.pcapng`                |
| Reverse Shell Simulation | `reverse_shell_simulation.pcapng` |

---

## Documentation

Detailed reports are available inside the `docs/` directory.

---

## Educational Purpose

This repository was created for educational purposes to understand packet-level behavior and network security concepts in a controlled lab environment.
