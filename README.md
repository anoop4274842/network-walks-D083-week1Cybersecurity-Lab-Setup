# network-walks-D083-week1Cybersecurity-Lab-Setup
Cybersecurity-Lab-Setup
# Cybersecurity Lab Setup – VirtualBox NAT Network

This project documents the setup of a private NAT Network in Oracle VirtualBox for a cybersecurity lab. The network allows virtual machines to communicate with each other and access external networks through VirtualBox NAT.

## 🎯 Objectives

- Configure a NAT Network in VirtualBox
- Create a private IPv4 network
- Enable DHCP for automatic IP address assignment
- Configure the network for future cybersecurity lab activities
- Document the laboratory network configuration

## 🧰 Lab Environment
 | Component | Configuration |
|---|---|
| Virtualization Platform | Oracle VirtualBox |
| Network Type | NAT Network |
| Network Name | `NatNetwork` |
| IPv4 Prefix | `10.0.0.2/24` |
| DHCP | Enabled |
| IPv6 | Disabled |

## ⚙️ Configuration Steps

### 1. Create a NAT Network in VirtualBox

1. Open **Oracle VirtualBox Manager**.
2. Go to **Tools → Network** (or **File → Tools → Network**, depending on your VirtualBox version).
3. Open the **NAT Networks** tab and create a NAT Network.
4. Set the network name to `NatNetwork`.
5. Set the IPv4 prefix to `10.0.0.0/24`.
6. Enable **DHCP** and apply the configuration
  ## ✅ Learning Outcomes

7. How to create a NAT Network in VirtualBox
How to configure an IPv4 network
How CIDR notation works
The purpose of DHCP
How virtual networking can be used to build a cybersecurity laboratory
The importance of documenting technical configurations

👤 Author

Anoop Gangadharan
Cybersecurity Learner | Offensive Security & VAPT
https://lnkd.in/p/gRH9hbX3

📌 Project Status

Status: Initial NAT Network Configuration Completed
