# Enterprise Network Simulation

## 🌐 Topology Overview
![Network Topology](Secure-Multi-Department-Enterprise-Edge2.png)

## 🛠️ Technologies Used
* **Platform:** Cisco Packet Tracer
* **Hardware:** Cisco ASA 5506-X, 2960 Switches, 2811 Router
* **Protocols:** VLANs (802.1Q), NAT/PAT, ICMP Inspection, Static Routing

## 🚀 Key Objectives
* Isolated Sales, IT, and HR departments using **VLANs**.
* Configured **ASA Firewall** for stateful packet inspection.
* Implemented **NAT** to provide internet access to private subnets.
* Resolved Spanning Tree **Native VLAN mismatches**.

## Troubleshooting Log:

* Spanning Tree: Resolved Native VLAN mismatches that were causing port blocking.
* Stateful Firewall: Configured ICMP inspection on the ASA to allow return traffic from the ISP.
* NAT: Implemented dynamic NAT to map private department subnets to a single public interface.
