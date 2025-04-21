# 🔐 Network Security Lab – ACL & Firewall Simulation

This project simulates a secure small office network using Cisco Packet Tracer.

## 📊 Topology Overview

- **VLANs** for Admin, Employee, Guest, and Server zones
- **Router-on-a-Stick** setup using subinterfaces
- **ACLs** applied:
  - ✅ Admin & Employee allowed access to Server
  - ❌ Guest denied access to Server

## 💡 Skills Demonstrated

- VLAN Configuration
- ACL Implementation
- Basic Firewall Rules (Packet Filtering)
- Network Segmentation
- Cisco IOS CLI

## 🖥️ IP Addressing

| Device    | VLAN | IP Address      |
|-----------|------|-----------------|
| Admin PC  | 10   | 192.168.10.2    |
| Employee  | 10   | 192.168.10.3    |
| Guest     | 20   | 192.168.20.2    |
| Server    | 30   | 192.168.30.2    |

## 📸 Infographic

![Network Topology](A_2D_digital_network_diagram_displays_a_small_offi.png)

## 📁 Files Included

- `network_security_lab.pkt` – Full simulation file
- PNG diagram of the topology
