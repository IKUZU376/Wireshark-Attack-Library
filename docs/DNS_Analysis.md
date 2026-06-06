# DNS Traffic Analysis

## Objective

Capture and analyze DNS query traffic generated during domain resolution.

---

## Tools Used

* Wireshark
* dig

---

## Command Used

```bash
dig google.com
```

---

## Observations

* DNS queries were transmitted to the resolver.
* Corresponding DNS responses were received.
* Domain name resolution completed successfully.

---

## Protocols Involved

* DNS
* UDP
* IPv4

---

## Security Relevance

DNS traffic is important for:

* Domain resolution
* Threat hunting
* DNS tunneling detection
* Malware communication analysis

---

## Evidence

* Capture File: `pcaps/dns_traffic.pcapng`
* Screenshot: `screenshots/dns_traffic.png`
