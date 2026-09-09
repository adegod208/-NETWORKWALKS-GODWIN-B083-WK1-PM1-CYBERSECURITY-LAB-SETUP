

# 🔐 Cybersecurity Lab Environment Setup

**My personal cybersecurity lab for hands-on practice with network security, pentesting tools, and vulnerable machines.**

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red) ![Ver](https://img.shields.io/badge/Ver-Virtualbox%20v7.2-blue)![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![Skill](https://img.shields.io/badge/Skill-Linux-black)![Network](https://img.shields.io/badge/Network-10.0.0.0%2F24-1abc9c) ![Penetration Testing](https://img.shields.io/badge/-Penetration%20Testing-red)

![Skill](https://img.shields.io/badge/Skill-Virtualization-red) ![GitHub](https://img.shields.io/badge/GitHub-black?logo=github) ![Kali Linux](https://img.shields.io/badge/Kali%20Linux-v2026.2-557C94?logo=kalilinux&logoColor=white) ![NetworkWalks](https://img.shields.io/badge/-NetworkWalks-darkred) ![Ethical Hacking](https://img.shields.io/badge/-Ethical%20Hacking-orange) ![Name](https://img.shields.io/badge/-ADEWUYI%20GODWIN%20OLUWAPELUMI-red?style=flat-square)

## 📌 Project Overview
This project focuses on setting up a **Cybersecurity and penetration-testing laboratory** using VirtualBox and Kali Linux.

The lab is designed to provide a secure and repeatable environment for conducting cybersecurity operations such as network scanning, reconnaissance, vulnerability analysis, and other security-testing practices.

The lab operates within a private virtual network, allowing for the future addition of machines that can serve as designated targets for authorized security testing.

---


## 🎯 Objectives
- Install and configure VirtualBox.
- Install/import Kali Linux as a virtual machine.
- Create a private **NAT Network** for the cybersecurity lab.
- Configure network connectivity for Kali Linux.
- Assign a consistent IP address to the Kali VM.
- Verify network connectivity and DNS resolution.
- Take a clean VM snapshot for recovery.
- Document the complete setup process.
- Prepare the environment for future cybersecurity projects.


## 🛡️ Purpose of the Lab
The lab offers a secure, isolated environment designed for cybersecurity education and authorized security testing.
It can also be used for activities such as:
- Password-cracking practice
- Firewall configuration and testing
- Intrusion detection and prevention exercises
- Malware analysis in a sandboxed setup
- Phishing and social engineering simulations
- Security patch deployment and validation
- Log monitoring and incident response drills
- Digital forensics and evidence collection

  ## ⚙️ Lab Configuration

| 🧩 Component       | ⚙️ Configuration   |
| ----------------- | ------------------ |
| 🖥️ Host OS        | Windows 11 pro        |
| 🧠 Host RAM        | 16 GB               |
| ⚡ Processor       | Intel Core i5      |
| 🧰 Hypervisor      | VirtualBox 7.2     |
| 🐉 Security OS     | Kali Linux 2026.2  |
| 🧠 Kali RAM        | 4251 MB            |
| 🌐 Virtual Network | NAT Network        |
| 📡 Network Address | 10.0.0.0/24        |
| 🐧 Kali IP Address | 10.0.0.2/24        |
| 🚪 Default Gateway | 10.0.0.1           |
| 🌍 DNS Server      | 8.8.8.8            |
| 🔮 Future VM Range | 10.0.0.3–10.0.0.99 |

---

# 🪜 Lab Setup Procedure  

## Step 1. Install 7-Zip  
7-Zip is installed to extract the Kali Linux virtual-machine package, which might be provided as a `.7z` archive.  

**Tool:** 7-Zip  

---  

## Step 2. Install VirtualBox  
VirtualBox is installed to act as the hypervisor.  

---  

## Step 3. Create the NAT Network  
A NAT Network is set up in VirtualBox.  
A dedicated NAT Network was created in VirtualBox.

Configuration:
Network Name: NatNetwork IPv4 Prefix:  10.0.0.0/24 DHCP:Enabled IPv6:Disabled
 ![network settings](Screenshot_2026-09-09_174215.png)

