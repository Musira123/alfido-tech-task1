# 🛡️ Task 1 - Reconnaissance & Scanning

**Internship:** Alfido Tech Cybersecurity Internship  
**Intern:** Masira Taj  
**Task:** Network Reconnaissance and Scanning using Netdiscover and Nmap

---

## 📝 Objective

The goal of this task was to perform reconnaissance on a local network to identify active hosts and scan a selected target for open ports, services, and OS details.

---

## 🧰 Tools Used

- **Netdiscover** – for live host discovery  
- **Nmap** – for port scanning, service/version detection, and OS fingerprinting

---

## 🔍 My Network Info

- **Local IP:** `192.168.64.xxx`
- **Network Range:** `192.168.64.0/24`
- **Target IP Selected:** `192.168.xx.xx`

---

## 🔹 Step-by-Step Summary

### 1. Discovering Devices on Network
```bash
sudo netdiscover -r 192.168.64.0/24
