# 🔐 Securing the Perimeter – Cybersecurity Project

![Status](https://img.shields.io/badge/status-Completed-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Author](https://img.shields.io/badge/author-T%20Harsha%20Vardhan-orange)
 
> **Project Type:** Cybersecurity Virtual Lab  
> **Platform Used:** VirtualBox, ELK Stack, Kali Linux, Ubuntu, Windows

---

## 📘 Overview

A major cryptocurrency exchange, **XYZ**, was hit with a cyberattack that led to the theft of over **500 BTC** due to poor perimeter security. This project aims to redesign their network securely, implement real-time threat monitoring using a **SIEM**, and guide the organization toward adopting a **Zero Trust Architecture**.

---

## 🛠️ Tools & Technologies Used

| Category       | Tools / OS                              |
|----------------|------------------------------------------|
| 🖥️ Virtualization | VirtualBox                             |
| 🧱 OS Platforms  | Kali Linux, Ubuntu, Windows             |
| 📊 SIEM Stack    | ELK Stack (Elasticsearch, Logstash, Kibana), Filebeat |
| 🌐 Design Tools  | draw.io for network architecture        |

---

## 📁 Project Structure
- `presentation/`: PowerPoint presentation
- `screenshots/`: Setup screenshots (VirtualBox, Filebeat, Kibana, etc.)
- `documentation/`: Zero Trust comparison and other reports
- `network-diagram/`: Updated draw.io network diagram


---

## 🔄 Project Phases

### ✅ Phase 1: Network Vulnerability Identification
- Analyzed XYZ’s insecure flat network.
- All servers were exposed directly to the internet.

### 🔄 Phase 2: Network Redesign
- Segmented network into:
  - **DMZ (Public & Private)** – Web & DB servers
  - **Internal Subnet** – Internal services
- Added **Firewalls** and **VPN** access for file servers.

### 📦 Phase 3: VirtualBox Lab Setup
- Configured 3 subnets:
  - `192.168.10.0/24` (Private-DMZ)
  - `192.168.20.0/24` (Public-DMZ)
  - `192.168.30.0/24` (Internal)

### 🔍 Phase 4: SIEM Setup (Monitoring)
- Installed **ELK Stack** on Private DMZ (Elk-Server)
- Installed **Filebeat** on Web Server (Public DMZ)
- Logs visualized in **Kibana**

### 🔐 Phase 5: Zero Trust Adoption
- Compared 3 Zero Trust principles to Traditional Security
- Recommended model: **Device Agent & Gateway**
- Ensures per-session access, encrypted communication, and continuous monitoring.

---

## 🖼️ Screenshots

> 📂 See the `screenshots/` folder for full visuals

- ✅ VirtualBox Subnet Configuration  
- ✅ ELK & Filebeat Running Status  
- ✅ Logs in Kibana  
- ✅ Network Connectivity Pings & Traceroutes  

---

## 🧠 Key Learning Outcomes

- Importance of network segmentation and firewalls.
- Hands-on setup of SIEM tools in a real-like virtual lab.
- Deep understanding of **Zero Trust Security** and its practical benefits.

---

## 🧾 License

This project is submitted as part of a cybersecurity lab. Educational use only.

---

## 🙋‍♂️ Author

**T Harsha Vardhan**  
[GitHub Profile](https://github.com/your-username)

---

> ⚠️ **Note:** This project simulates a real-world attack and remediation strategy. It does not use real data or production systems.

