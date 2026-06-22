# 🏦 Banking Network Infrastructure

## 📌 Project Overview

This project presents a complete **Banking Network Infrastructure Design** built using Cisco networking technologies. The network is designed to provide **high availability, security, scalability, and efficient traffic management** for a banking environment.

The infrastructure includes redundant core switches, firewall protection, ATM network isolation, voice services, server segmentation, and secure remote management.

---

## 🎯 Project Objectives

* Design a secure banking network architecture.
* Implement network redundancy and failover mechanisms.
* Segment departments using VLANs.
* Protect critical banking services through security policies.
* Enable secure communication and management.
* Ensure business continuity through HSRP and OSPF.

---

## 🏗️ Network Architecture

### Core Components

* 🌐 Edge Router
* 🔥 Zone-Based Firewall (ZBF)
* 🔄 Dual Core Switches (HSRP)
* 📞 Call Center Network
* 🏧 ATM Network
* 🖥️ Internal Servers
* 📹 CCTV & Security Network
* 📊 Logging & Monitoring Infrastructure

---

## 🖧 VLAN Structure

| VLAN | Department                      |
| ---- | ------------------------------- |
| 10   | 💰 Tellers & Cash Desks         |
| 20   | 📞 Voice / Call Center          |
| 30   | 📄 Credit & Business Operations |
| 40   | 🏧 ATM Network                  |
| 50   | 📹 Security & CCTV              |
| 60   | 🖥️ Internal Servers            |
| 70   | 📊 Logging Servers              |
| 99   | ⚙️ Management Network           |

---

## ⚙️ Technologies Used

* Cisco IOS
* OSPF Routing Protocol
* HSRP (High Availability)
* VLAN Segmentation
* Inter-VLAN Routing
* NAT
* ACLs
* DHCP
* SSH
* SNMP
* QoS
* Port Security
* Rapid PVST+
* Zone-Based Firewall

---

## 🔒 Security Features

### Network Security

* SSH Secure Management
* ACL-Based Traffic Filtering
* ATM Network Isolation
* Voice VLAN Restrictions
* Port Security
* Management VLAN Protection
* Firewall Security Policies

### Access Control

* User Authentication
* Secure Administrative Access
* Device Hardening

---

## 🔄 High Availability

### HSRP

Provides gateway redundancy between:

* Core Switch 1 (Primary)
* Core Switch 2 (Standby)

### OSPF

Provides dynamic routing and fast convergence across the banking infrastructure.

---

## 📈 Quality of Service (QoS)

Voice traffic is prioritized to ensure:

* Low latency
* Reduced jitter
* High-quality VoIP communication

---

## 🏧 ATM Network Security

ATM devices are isolated from internal user networks.

Allowed Services:

* HTTPS (443)
* HTTP (80)
* DNS (53)

Blocked Access:

* User VLANs
* Sensitive Internal Resources

---

## 📁 Project Contents

```bash
Banking-Network-Infrastructure/
│
├── Banking Network Infrastructure.pdf
├── Network Diagram
├── Router Configurations
├── Firewall Configuration
├── Core Switch Configurations
├── Access Switch Configurations
├── DHCP Configuration
└── Security Policies
```

---

## 🚀 Key Features

✅ High Availability using HSRP

✅ Dynamic Routing using OSPF

✅ Secure Remote Access using SSH

✅ ATM Isolation and Protection

✅ VLAN Segmentation

✅ Firewall Protection

✅ QoS for Voice Traffic

✅ Port Security

✅ DHCP Services

✅ SNMP Monitoring

---

## 👨‍💻 Author

**Ahmed Mohamed Wagih**

🌐 Network Engineer

🔐 Cyber Security Enthusiast

📡 NOC Engineer

### Connect With Me

* LinkedIn: [www.linkedin.com/in/ahmed-mohamed-wagih-a9a589411](http://www.linkedin.com/in/ahmed-mohamed-wagih-a9a589411)
* GitHub: https://github.com/Ahmed-neb

---

⭐ If you found this project useful, don't forget to star the repository.
