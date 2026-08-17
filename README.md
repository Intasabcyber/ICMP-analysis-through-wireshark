# ICMP Traffic Analysis Using Wireshark

## 📌 Project Overview

This project documents a hands-on analysis of **ICMP (Internet Control Message Protocol)** traffic using Wireshark.

The analysis focuses on identifying and interpreting ICMP Echo Request and Echo Reply packets and understanding their relationship at the packet level.

---

## 🎯 Objectives

* Understand the purpose of ICMP in network communication
* Identify ICMP Echo Request and Echo Reply packets
* Analyze ICMP packet fields
* Examine source and destination IP addresses
* Understand TTL values
* Relate ICMP request and response packets
* Practice packet analysis using Wireshark

---

## 🛠️ Tools & Environment

* **Tool:** Wireshark
* **Analysis Type:** Packet Capture Analysis
* **Protocol:** ICMP
* **Capture Format:** PCAP/PCAPNG

---

## 🔎 Analysis Performed

### 1. ICMP Echo Request

The ICMP Echo Request packet was identified as:

* **ICMP Type:** 8
* **Code:** 0

An Echo Request is sent to determine whether a destination host is reachable and responsive.

### 2. ICMP Echo Reply

The corresponding response was identified as:

* **ICMP Type:** 0
* **Code:** 0

An Echo Reply indicates that the destination responded to the Echo Request.

### 3. Source and Destination Analysis

The packet headers were examined to identify:

* Source IP address
* Destination IP address
* Protocol information
* Packet length
* Time sequence

### 4. TTL Analysis

The **Time To Live (TTL)** field was examined as part of the IP header analysis.

TTL helps limit the lifetime of an IP packet as it travels through a network.

---

## 📸 Evidence

Screenshots documenting the analysis are organized and numbered for easier verification.

| Screenshot | Description                     |
| ---------- | ------------------------------- |
| 01         | ICMP packet overview            |
| 02         | ICMP Echo Request — Type 8      |
| 03         | ICMP Echo Reply — Type 0        |
| 04         | Request ↔ Response relationship |
| 05         | ICMP Statistics
| 06         | TTL Comparison
| 07         | TYPE 3 AND TYPE 11 Filters

---

## 🔐 Cybersecurity Relevance

ICMP analysis is useful in network security and troubleshooting because it helps analysts understand network reachability, communication patterns, and packet behavior.

Packet analysis skills can also contribute to identifying unusual or unexpected network activity during security investigations.

---

## 📚 Key Learning Outcomes

Through this analysis, I practiced:

* Wireshark packet filtering
* ICMP protocol identification
* Packet header analysis
* Source/destination investigation
* Request-response correlation
* Network traffic documentation

---

## 📝 Conclusion

This lab provided practical experience in analyzing ICMP traffic using Wireshark and strengthened my understanding of how network communication can be examined at the packet level.

---

## 👤 Author

**Intasab Fatima**

Cybersecurity Student | Networking & Linux

---

⭐ This repository is part of my ongoing cybersecurity learning portfolio.
