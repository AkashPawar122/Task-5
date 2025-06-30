# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## 📌 Objective:
Capture live network traffic using Wireshark and identify at least 3 different network protocols.

## 🛠 Tools Used:
- Wireshark
- Command Prompt (CMD)
- Web Browser

## 📝 Steps Followed:
1. Installed Wireshark and selected the active Wi-Fi interface for capturing.
2. Generated traffic by pinging `google.com` via CMD and visiting websites like google.com and bing.com.
3. Captured packets for 30–40 seconds and then stopped the capture.
4. Applied protocol filters: `dns`, `tcp`, `udp`, `http` to analyze traffic.
5. Saved the packet capture file as `task5-capture.pcapng`.
6. Took 4 screenshots showing different protocols.

## 📦 Protocols Identified:
- **ARP** – Resolves IP to MAC address in local networks.
- **DNS** – Resolves domain names to IP addresses.
- **TCP** – Reliable transmission protocol (observed handshake and ACK).
- **UDP/QUIC** – Fast, connectionless protocol used in DNS and encrypted QUIC traffic.

## 📁 Submission Files:
- `task5-capture.pcapng` – Wireshark capture file
- `screenshots` – Contains 4 filtered protocol screenshots
- `README.md` – This file (submitted in text format)

## 🎯 Outcome:
Gained hands-on experience with real-time packet capture, traffic generation, and protocol analysis using Wireshark.
