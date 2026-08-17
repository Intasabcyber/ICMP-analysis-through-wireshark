# ICMP Traffic Analysis Using Wireshark

## 📌 Project Overview
This project documents a hands-on analysis of **ICMP (Internet Control Message Protocol)** traffic using Wireshark.

The analysis focuses on identifying and interpreting ICMP Echo Request and Echo Reply packets and understanding their relationship at the packet level.

---

## 🎯 Objectives
- Understand the purpose of ICMP in network communication
- Identify ICMP Echo Request and Echo Reply packets
- Analyze ICMP packet fields
- Examine source and destination IP addresses
- Understand TTL values
- Relate ICMP request and response packets
- Practice packet analysis using Wireshark

---

## 🛠️ Tools & Environment
- **Tool:** Wireshark
- **Analysis Type:** Packet Capture Analysis
- **Protocol:** ICMP
- **Capture Format:** PCAP/PCAPNG

---

## 🔎 Analysis Performed

### 1. ICMP Echo Request
![ICMP Echo Request](<ICMP TYPE REQUEST.png>)

The ICMP Echo Request packet was identified as:
- **ICMP Type:** 8
- **Code:** 0

An Echo Request is sent to determine whether a destination host is reachable and responsive.

### 2. ICMP Echo Reply
![ICMP Echo Reply](<ICMP TYPE REPLY.png>)

The corresponding response was identified as:
- **ICMP Type:** 0
- **Code:** 0

An Echo Reply indicates that the destination responded to the Echo Request.

### 3. Source and Destination Analysis
![ICMP Packets Overview](<ICMP PACKETS OVERVIEW.png>)

The packet headers were examined to identify:
- Source IP address
- Destination IP address
- Protocol information
- Packet length
- Time sequence

### 4. TTL Analysis
![TTL Comparison](<TTL comparison.png>)

The **Time To Live (TTL)** field was examined as part of the IP header analysis.

TTL helps limit the lifetime of an IP packet as it travels through a network.

### 5. ICMP Statistics
![Statistics Conversation](<STATISTICS CONVERSATION.png>)

Wireshark's Statistics → Conversations view was used to summarize ICMP traffic between hosts.

### 6. Type 3 and Type 11 Filters
![Type 3 Filter](<TYPE 3 FILTER.png>)
![Type 11 Filter](<TYPE 11 FILTER.png>)

- **Type 3:** Destination Unreachable
- **Type 11:** Time Exceeded (commonly seen during traceroute)

---

## 📸 Evidence Summary

| Screenshot | Description                     |
| ---------- | -------------------------------- |
| 01         | ICMP packet overview             |
| 02         | ICMP Echo Request — Type 8       |
| 03         | ICMP Echo Reply — Type 0         |
| 04         | Request ↔ Response relationship  |
| 05         | ICMP Statistics                  |
| 06         | TTL Comparison                   |
| 07         | Type 3 and Type 11 Filters       |

---

## 🔐 Cybersecurity Relevance
ICMP analysis is useful in network security and troubleshooting because it helps analysts understand network reachability, communication patterns, and packet behavior.

Packet analysis skills can also contribute to identifying unusual or unexpected network activity during security investigations.

---

## 📚 Key Learning Outcomes
Through this analysis, I practiced:
- Wireshark packet filtering
- ICMP protocol identification
- Packet header analysis
- Source/destination investigation
- Request-response correlation
- Network traffic documentation

---

## 📝 Conclusion
This lab provided practical experience in analyzing ICMP traffic using Wireshark and strengthened my understanding of how network communication can be examined at the packet level.

---

## 👤 Author
**Intasab Fatima**
Cybersecurity Student | Networking & Linux

---

⭐ This repository is part of my ongoing cybersecurity learning portfolio.
