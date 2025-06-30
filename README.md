# 🛡️ Task 5 - Network Traffic Capture & Protocol Analysis (Wireshark)

## 📌 Objective
Capture live network packets using Wireshark and identify basic network protocols in the traffic.

---

## 🧰 Tools Used
- **Wireshark**: Network protocol analyzer for capturing and analyzing packets.
- **Operating System**: Windows 11

---

## 📦 Steps Performed

1. **Installed Wireshark** from [https://www.wireshark.org/](https://www.wireshark.org/).
2. **Started a live capture** on the active interface (`Wi-Fi`/`Ethernet`).
3. **Generated traffic** by:
   - Browsing websites (e.g., `example.com`)
   - Accessing local network services
4. **Stopped the capture** after approximately 1 minute.
5. **Applied filters** in Wireshark to analyze protocols.
6. **Identified and noted down** multiple distinct protocols.
7. **Exported the capture** as a `.pcap` file.
8. **Compiled this short report.**

---

## 🔍 Protocols Identified

| Protocol     | Description                                         | Notes / Packet Example                            |
|--------------|-----------------------------------------------------|---------------------------------------------------|
| **TCP**      | Transmission Control Protocol                      | Reliable, connection-based communication          |
| **UDP**      | User Datagram Protocol                              | Lightweight, connectionless communication         |
| **HTTP**     | HyperText Transfer Protocol                         | Web traffic, GET/POST requests                    |
| **DNS**      | Domain Name System                                  | Resolving domain names to IP addresses            |
| **TLSv1.2**  | Transport Layer Security v1.2                       | Encrypted HTTPS traffic                           |
| **QUIC**     | UDP-based protocol for faster web traffic (used by Google) | Observed in modern browser traffic         |
| **mDNS**     | Multicast DNS                                       | Local name resolution without a central DNS       |
| **SSDP**     | Simple Service Discovery Protocol                   | Used in UPnP for device discovery                 |
| **ARP**      | Address Resolution Protocol                         | Resolves MAC addresses from IP addresses          |
| **DHCPv6**   | Dynamic Host Configuration Protocol for IPv6       | Assigns IPv6 addresses dynamically                |

---

## 📸 Screenshots

### 🖥️ Live Capture in Progress


### 🌐 DNS Traffic Filtered


### 🔐 TLSv1.2 Packets


### 📊 Protocol Hierarchy View


---

## 📁 Files Included

- `traffic_capture.pcapng`: Captured network traffic.
- `screenshots/`: Folder containing evidence of capture and protocol identification.
- `README.md`: This documentation/report.

---

## 🧠 Key Learnings

- Gained hands-on experience capturing and analyzing network traffic.
- Learned how various protocols behave and communicate on the network.
- Developed skills in filtering and interpreting raw packet data.

---

## 🧪 Filters Used in Wireshark

```wireshark
http
dns
tcp
udp
tls
quic
mdns
ssdp
arp
dhcpv6
