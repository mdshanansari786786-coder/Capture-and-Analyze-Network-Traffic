# Wireshark Packet Capture & Analysis  
### Objective  
Capture live network traffic using Wireshark, identify common network protocols, and export the results as a .pcap file.

---

## 📦 Tools Required  
- *Wireshark* (Free and open-source packet analyzer)

---

## 📝 Steps Performed  

### 1. Install Wireshark  
Download from the official website and install with default options.  
Ensure *Npcap* is included for packet capturing.

---

### 2. Start Packet Capture  
1. Open Wireshark.  
2. Select your active network interface (Wi-Fi/Ethernet).  
3. Click *Start Capture*.

---

### 3. Generate Network Traffic  
To generate packets for analysis, perform activities such as:  
- Browsing a website  
- Pinging a server  
- Opening multiple tabs

Example command used:
ping google.com


---

### 4. Stop the Capture  
After 1 minute of traffic generation, click the *Stop* button.

---

## 🔍 Protocol Analysis  

### Applied Filters  
Common Wireshark filter commands used:

| Protocol | Filter |
|---------|--------|
| DNS | dns |
| HTTP | http |
| HTTPS/TLS | tls |
| TCP | tcp |
| ICMP | icmp |

---

## 📡 Protocols Identified  
At least *three protocols* were identified in the packet capture:

### 1. DNS  
- Purpose: Resolves domain names to IP addresses  
- Observed DNS queries to external DNS servers.

### 2. TCP  
- Purpose: Handles reliable communication between devices  
- Observed SYN, SYN/ACK, ACK (3-way handshake).

### 3. ICMP  
- Purpose: Network diagnostics and ping operations  
- Produced when using ping google.com.

You may also find HTTPS/TLS packets when browsing websites.

---

## 💾 Exporting Packet Capture  
All packets were saved as:

capture_all.pcapng


Steps followed:  
*File → Save As → Select .pcapng → Save*

---

## 📈 Summary  
- Successfully captured live network traffic  
- Filtered and analyzed key protocols (DNS, TCP, ICMP)  
- Exported full packet capture file  
- Gained practical experience with Wireshark filtering and packet inspection

---

## 📂 Deliverables  
- *Packet Capture File (.pcapng)*  
- *Analysis Report (this README.md)*

---
