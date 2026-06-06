# HTTP Traffic Analysis

## Objective

Capture and analyze HTTP communication between a client and a locally hosted web server.

---

## Tools Used

* Wireshark
* Python HTTP Server
* curl

---

## Commands Used

### Start Server

```bash
python3 -m http.server 8000
```

### Generate Request

```bash
curl http://192.168.1.104:8000
```

---

## Observations

* HTTP GET requests were observed.
* The server responded with HTTP 200 OK.
* HTML content was returned successfully.

---

## Protocols Involved

* HTTP
* TCP
* IPv4

---

## Security Relevance

HTTP analysis is useful for:

* Web traffic inspection
* Request analysis
* Detecting insecure communication
* Understanding application behavior

---

## Evidence

* Capture File: `pcaps/http_traffic.pcapng`
* Screenshot: `screenshots/http_traffic.png`
