# Wireshark-Traffic-Analysis
# Task 5 – Capture and Analyze Network Traffic Using Wireshark

##  Objective
The objective of this task is to capture live network traffic using Wireshark and analyze basic network protocols such as DNS, TCP, UDP, and HTTP/TLS.

---

##  Tool Used
- Wireshark (Network Protocol Analyzer)

---

##  Procedure Followed

1. Installed Wireshark along with Npcap.
2. Opened Wireshark and selected the active Wi-Fi network interface.
3. Started packet capture.
4. Generated network traffic by browsing websites and using the ping command.
5. Stopped the capture after approximately one minute.
6. Applied display filters such as:
   - dns
   - tcp
   - udp
   - http / tls
7. Analyzed packet details including source IP, destination IP, and port numbers.
8. Saved the capture file in `.pcapng` format.

---

##  Protocols Identified

### 1️.DNS (Domain Name System)
- Used to resolve domain names into IP addresses.
- Observed DNS query and response packets.
- DNS typically uses UDP port 53.

### 2️. TCP (Transmission Control Protocol)
- Connection-oriented and reliable protocol.
- Observed TCP 3-way handshake (SYN, SYN-ACK, ACK).
- Used for reliable data transfer.

### 3️. UDP (User Datagram Protocol)
- Connectionless and faster protocol.
- Used in DNS communication.
- Does not guarantee delivery.

### 4️. HTTP / TLS
- HTTP is used for web communication.
- TLS provides encrypted communication for secure websites (HTTPS).

---

## Observations

- Captured real-time network traffic from browser activity.
- Identified different protocols and packet types.
- Observed IP addresses, port numbers, and protocol behavior.
- Understood how DNS queries resolve domain names before establishing a connection.

---

## 🎯 Outcome

Successfully captured and analyzed live network traffic using Wireshark.  
Gained practical understanding of packet capture, protocol analysis, and basic network communication concepts.


