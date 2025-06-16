# Network Security Redesign - Full Overview

## 🧩 Project Scenario

XYZ Crypto Exchange faced a perimeter breach due to insecure network architecture. This project redesigned their network and deployed SIEM tools to monitor and prevent future attacks.

---

## 🛠️ Redesigned Network

- Segmented the network into:
  - DMZ (public services)
  - Internal (private servers)
- Added Firewalls between segments
- VPN enabled for secure file server access

---

## 💻 Virtual Environment Setup (VirtualBox)

- **DMZ VNet**
  - Public Subnet: Ubuntu Web Servers, Filebeat
  - Private Subnet: Kali DB Server, ELK Stack

- **Internal VNet**
  - Subnet: Windows Server (internal)

- IP Subnets used:
  - DMZ-Public: `192.168.20.0/24`
  - DMZ-Private: `192.168.10.0/24`
  - Internal: `192.168.30.0/24`

---

## 🧪 SIEM Deployment

- Installed **ELK stack** on DB subnet
- Installed **Filebeat** on web server
- Verified logs in **Kibana**

---

## 🔁 Result

- Better network isolation
- Centralized log monitoring
- Reduced risk of future breaches
