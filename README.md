# Network Scanner

This is a simple network scanning tool built using Python and the Scapy library. It discovers active devices on a network by sending ARP requests and displays their IP and MAC addresses.

## Installation

This project requires `scapy`. Install it using pip:

```bash
pip install scapy
```

## Usage

The script scans the network specified by the IP range "192.168.0.0/24". You can modify the `scan` function's argument to target a different network range.

```bash
python network_scanner.py
