# 🛡️ Task 5 - Network Traffic Capture & Protocol Analysis (Wireshark)

## 📌 Objective
Capture live network packets using Wireshark and identify basic network protocols in the traffic.

---

## 🧰 Tools Used
- **Wireshark**: Network protocol analyzer for capturing and analyzing packets.
- **Operating System**: [Your OS - e.g., Windows 10 / Ubuntu 22.04]

---

## 📦 Steps Performed

1. **Installed Wireshark** from [https://www.wireshark.org/](https://www.wireshark.org/).
2. **Started a live capture** on the active interface (`Wi-Fi`/`Ethernet`).
3. **Generated traffic** by:
   - Browsing websites (e.g., `example.com`)
   - Running terminal commands (`ping google.com`)
4. **Stopped the capture** after approximately 1 minute.
5. **Applied filters** in Wireshark to analyze protocols.
6. **Identified and noted down** at least 3 distinct protocols.
7. **Exported the capture** as a `.pcap` file.
8. **Compiled this short report.**

---

## 🔍 Protocols Identified

| Protocol | Description                     | Example Packet Info / Notes               |
|----------|----------------------------------|-------------------------------------------|
| **TCP**  | Transmission Control Protocol    | Handshake packets, reliable data transfer |
| **DNS**  | Domain Name System               | DNS queries and responses                 |
| **HTTP** | HyperText Transfer Protocol      | Web browsing requests/responses           |

> You may also include protocols like ICMP (ping), ARP, HTTPS, etc., if observed.

---

## 📸 Screenshots

### 🖥️ Live Capture in Progress


### 🗂️ Filtered DNS Traffic


### 📶 Protocol Hierarchy Display



## 📁 Files Included

- `traffic_capture.pcap`: Raw packet capture file.
- `README.md`: This report file.

---

## 🧠 Key Learnings

- Understood how to use Wireshark to monitor real-time traffic.
- Learned to apply protocol filters (e.g., `http`, `dns`, `tcp`) for better analysis.
- Observed differences in how various protocols behave on the network.

---

## 🧪 Sample Filters Used

```wireshark
http
dns
tcp
icmp
