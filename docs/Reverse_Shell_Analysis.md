
# Reverse Shell Simulation Analysis

## Objective

Capture and analyze traffic generated during a simulated reverse shell communication using Netcat.

---

## Tools Used

* Wireshark
* Netcat

---

## Commands Used

### Listener

```bash
nc -lvnp 4444
```

### Client

```bash
nc localhost 4444
```

---

## Observations

* TCP connection established over port 4444.
* Data packets carrying user input were exchanged successfully.
* TCP session termination packets were observed.

---

## Protocols Involved

* TCP
* IPv4

---

## Security Relevance

Reverse shell traffic is frequently encountered during post-exploitation activities and is useful for understanding attacker communication patterns.

---

## Evidence

* Capture File: `pcaps/reverse_shell_simulation.pcapng`
* Screenshot: `screenshots/reverse_shell_simulation.png`

