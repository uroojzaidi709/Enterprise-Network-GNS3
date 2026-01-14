# Enterprise Network Implementation (GNS3)
Enterprise network implementation using GNS3 with VLANs, OSPF, STP, EtherChannel, NAT, and Site-to-Site IPsec VPN.

## 📌 Project Overview
This project demonstrates the design and implementation of a secure and scalable enterprise network. It connects a Head Office (HQ) and a Branch Office through a Site-to-Site IPsec VPN while implementing redundancy and dynamic routing.

## 🧱 Network Architecture
- **Three-Tier Design:** Core, Distribution, and Access Layer.
- **Segmentation:** Multiple VLANs for departmental isolation (HR, IT, Sales, Finance).
- **Redundancy:** High availability using EtherChannel and STP.
- **Secure WAN:** Encrypted communication using IPsec VPN through an ISP cloud.

## 🛠 Technologies & Protocols
- **Switching:** VLAN, VTP (Server/Client), DTP, STP (Root Bridge), EtherChannel (LACP/PAgP).
- **Routing:** OSPF (Dynamic), Router-on-a-Stick (Inter-VLAN Routing).
- **Security:** IPsec VPN (IKEv1, AES Encryption), Extended ACLs.
- **IP Services:** NAT/PAT for internet/WAN access.

## 🗂 VLAN Information
| VLAN ID | Department | Subnet |
|------|-----------|-----------|
| 10 | HR | 192.168.10.0/24 |
| 20 | IT | 192.168.20.0/24 |
| 30 | Sales | 192.168.30.0/24 |
| 40 | Finance | 192.168.40.0/24 |

## 📁 Repository Structure
* **[/Topology](https://github.com/uroojzaidi709/Enterprise-Network-GNS3/tree/main/Topology)**: Contains the `.gns3` project files. (Note: These are backend files that appear as raw text on GitHub).
* **[/Screenshots](https://github.com/uroojzaidi709/Enterprise-Network-GNS3/tree/main/Screenshots)**: Visual verification including Topology, OSPF, and VPN (Phase 1, 2, 3) status.
* **[/Config](https://github.com/uroojzaidi709/Enterprise-Network-GNS3/tree/main/Config)**: Running configurations for HQ, ISP, and Branch routers.
* **[/Report](https://github.com/uroojzaidi709/Enterprise-Network-GNS3/tree/main/Report)**: Contains **CCN REPORT (2).pdf** with 51 implementation steps and test results.
