# 🏡 Small Home Network (Cisco Packet Tracer)

This is a simple Layer 2 + Layer 3 network topology built using **Cisco Packet Tracer**, intended to demonstrate basic IP addressing, routing, and switch-router communication.

---

## 🧱 Network Topology Overview

- **4 PCs** (end devices)
- **2 Switches** (Layer 2)
- **1 Router** (Layer 3)
- **Static IP addressing**
- **Routing between two subnets**
- **No DHCP or NAT in this version**

---

## 🔧 Configuration Summary

| Device | IP Address     | Subnet Mask       | Gateway         |
|--------|----------------|-------------------|------------------|
| PC0    | 192.168.1.10   | 255.255.255.0     | 192.168.1.1      |
| PC1    | 192.168.1.11   | 255.255.255.0     | 192.168.1.1      |
| PC2    | 192.168.2.10   | 255.255.255.0     | 192.168.2.1      |
| PC3    | 192.168.2.11   | 255.255.255.0     | 192.168.2.1      |

Router interfaces:
- `Gig0/0` – 192.168.1.1
- `Gig0/1` – 192.168.2.1

---

## 🌐 Flowchart: Packet Flow

![Network Flowchart](docs/network_flowchart.png)

---

## 🚀 How to Run

1. Download and install **Cisco Packet Tracer**
2. Clone this repository:
   ```bash
   git clone https://github.com/nethaxstark/
