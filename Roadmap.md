# 🛡️ Cybersecurity Lab Journal

**Welcome to my technical documentation repository.**

This repository serves as a living journal of my journey into **Blue Teaming and SOC Analysis**. Here, I document the construction, configuration, and monitoring of my virtualized Home Lab environment. 

The goal of this project is to move beyond theory and gain hands-on experience with the tools and tactics used in modern Security Operations Centers.

## 🏗️ Lab Architecture

My lab is hosted on **VMware Workstation** and currently consists of the following isolated networks:

* **Attacker Node:** Kali Linux (Red Team tools, Nmap, Hydra, Metasploit)
* **Defender/SIEM Node:** Ubuntu Server running **Wazuh Manager** & Dashboard
* **Target A:** Windows 10 (Joined to Domain, Sysmon installed)
* **Target B:** Windows Server (Domain Controller / Active Directory)
* **Target C:** Metasploitable (Vulnerable Web App testing)

## 📂 Repository Structure

I organize my repository by topic to follow my learning roadmap:

* **00-Lab-Setup/**
  Documentation of my VMware settings, IP addressing plan, and machine specs.

* **01-Networking/**
  Practical labs on OSI model, analyzing PCAP files with Wireshark, and understanding protocols (DNS, TCP/IP).

* **02-OS-Fundamentals/**
  Notes on Windows Event Viewer, Sysmon configuration, and Linux logging (`/var/log`).

* **03-Wazuh-Project/**
  My implementation of Wazuh SIEM, including agent installation and custom alert rules.




## 🚀 2026 Roadmap & Progress

- [ ] **Phase 1:** Networking Fundamentals (Packet Analysis)
- [ ] **Phase 2:** Windows & Linux OS Internals (Event IDs, Logs)
- [ ] **Phase 3:** SIEM Integration (Wazuh/Splunk) & Log Aggregation
- [ ] **Phase 4:** Adversary Emulation & Threat Hunting

## 🔧 Tools & Technologies
* **Virtualization:** VMware
* **SIEM:** Wazuh
* **Network Analysis:** Wireshark, Tcpdump
* **Endpoint Visibility:** Sysmon
* **Operating Systems:** Linux (Ubuntu, Kali), Windows

---
*Connect with me on [LinkedIn](https://www.linkedin.com/in/swetlana-jha-aaa57b339/) to follow my weekly updates.*
