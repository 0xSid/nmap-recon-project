# 🛠️ Nmap Reconnaissance Project

## 🧠 Objective
This project demonstrates how to use **Nmap** for real-world network reconnaissance. It includes scanning live hosts, identifying open ports, fingerprinting operating systems, and collecting service details using Nmap in a Kali Linux environment.



## 🛠 Tools Used
- Kali Linux
- Nmap
- VirtualBox
- scanme.nmap.org (official Nmap test host)



## 🔍 Scan Summary

| Scan Type | Command | File |
|-----------|---------|------|
| Ping Sweep | `nmap -sn scanme.nmap.org` | `ping-sweep.txt` |
| Port & Service Detection | `nmap -sS -sV scanme.nmap.org` | `port-service-scan.txt` |
| OS Detection | `nmap -O scanme.nmap.org` | `os-detection.txt` |
| Full Recon | `nmap -A -T4 scanme.nmap.org` | `full-recon.txt` |



## 📁 Project Structure
nmap-recon-project/
├── ScreenShots/
│ ├── Screenshot 1–4 (Nmap commands + results)
├── scans/
│ ├── ping-sweep.txt
│ ├── port-service-scan.txt
│ ├── os-detection.txt
│ └── full-recon.txt



## 📸 Sample Screenshots
<img src="ScreenShots/Screenshot 2025-05-08 112958.png" width="600"/>



## ✅ Findings
- Open ports: **22 (SSH)**, **80 (HTTP)**
- Services: Apache 2.4.7, OpenSSH 6.6
- OS Fingerprinting: Ubuntu 12.13 (Guessed)
- Traceroute completed in 1 hop
- Used aggressive Nmap scanning flags (`-A`, `-T4`) for in-depth fingerprinting



## 🧾 Conclusion
This project showcases the power of Nmap in performing structured reconnaissance. By saving, analyzing, and documenting each scan, it simulates the workflow of a real penetration tester or security analyst.



📘 **For Educational Use Only**
