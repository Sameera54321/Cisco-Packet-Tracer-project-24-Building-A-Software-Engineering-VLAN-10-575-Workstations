# Cisco-Packet-Tracer-project-24-Building-A-Software-Engineering-VLAN-10-575-Workstations
I’m excited to share my latest Cisco Packet Tracer project – Building A (Software Engineering) – a high‑density network simulation of an entire building dedicated to a software engineering department. The topology features 575+ desktop PCs (PC1 … PC575+), all operating within VLAN 10 (Software Engineering Plan 10).

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-24-Building-A-Software-Engineering-VLAN-10-575-Workstations/blob/main/13.jpg?raw=true)

## 📌 Summary

### Building A – Software Engineering (VLAN 10) is a Cisco Packet Tracer simulation that models a single building occupied by a software engineering department. The network includes:

    575+ desktop PCs (PC1 through PC575 and more)

    Multiple access switches (e.g., Cisco 2960‑24TT) to connect all workstations

    A dedicated VLAN (VLAN 10 – Software Engineering) for traffic isolation

    A router or Layer 3 switch for inter‑VLAN routing (if other departments exist)

    Central servers (optional) – file server, print server, or Git server within VLAN 10

### The project explores:

    VLAN creation and assigning hundreds of switch ports to VLAN 10

    Switch stacking or trunking to handle a large number of access ports

    DHCP configuration (on router or server) with a large IP scope (e.g., 192.168.10.0/23 for 510+ addresses)

    Port security (sticky MAC, max MAC addresses) on access ports

    Spanning‑Tree Protocol (STP) for redundant links

    Broadcast domain management – how a single VLAN behaves with 575+ hosts

    Scalability testing – switch CAM table size, broadcast traffic, and convergence

## ✨ Features

    ✅ 575+ workstations (PC1 … PC575+) – realistic large department

    ✅ Dedicated VLAN 10 (Software Engineering) – isolates traffic

    ✅ Multiple Cisco 2960 switches – provide sufficient access ports

    ✅ DHCP service – automatic IP assignment for all PCs

    ✅ Central servers (optional) – file, print, or development services

    ✅ Port security – prevents unauthorised device connections

    ✅ Scalability demonstration – manage 575+ hosts in a single broadcast domain (or routed)

    ✅ Full Packet Tracer file (.pkt) – ready to open and test

    ✅ Documentation – IP addressing plan, VLAN mapping, switch configs, DHCP scope

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – switch, router, and server configurations

    (Optional) Python – for generating PC hostnames or IP lists

## 🤝 Contributing

### Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more departments (e.g., Finance, HR, IT) with their own VLANs and inter‑VLAN routing.

    Implement VTP (VLAN Trunking Protocol) for centralised VLAN management.

    Add access control lists (ACLs) to restrict inter‑department traffic.

    Introduce wireless access points for a guest VLAN.

    Set up a syslog server to monitor switch port events.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
