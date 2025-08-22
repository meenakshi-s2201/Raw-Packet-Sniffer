# 🕵️‍♂️ Raw Packet Sniffer
    A lightweight network packet sniffer written in Python using raw sockets that captures Ethernet frames and decodes IPv4, TCP, UDP, and ICMP headers in a human-readable format.

## ⚙️ Requirements
    - Python 3.x
    - Root/Admin privileges (for raw socket access)
    - Linux-based OS (uses AF_PACKET which is specific to Linux)

## ✨ Features
    - Captures and parses Ethernet frames
    - Decodes IPv4 packets
    - Supports ICMP, TCP, and UDP protocols
    - Displays packet structure in a readable, indented hierarchy (with payload shown in multi-line hex view)
    - Runs without external libraries (pure Python standard library).

## 🚀 Installation & Usage

### Clone the repository:
    git clone https://github.com/your-username/raw-packet-sniffer.git
    cd raw-packet-sniffer

### Run the sniffer (requires sudo):
    sudo python3 packet_sniffer.py

### Stop the program with CTRL + C.

