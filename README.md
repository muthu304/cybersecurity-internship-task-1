# 🔐 Cybersecurity Internship – Task 1: Network Reconnaissance using Nmap

## 🧭 Objective

Learn and apply basic network reconnaissance techniques using `Nmap` to identify live hosts, scan ports, understand service exposure, and document findings as part of an internship project.

---

## 🧰 Tools & Environment

- **OS Used**: Kali Linux
- **Scan Tool**: [Nmap](https://nmap.org/) v7.95
- **Network**: Mobile Hotspot (Private Subnet)
- **IP Range Scanned**: `192.168.142.0/24`
- **Command Used**:
  ```bash
  sudo nmap -sS 192.168.142.0/24 -oN scan_results.txt


##🔍 Scan Results Summary

-🔎 Total IPs scanned: 192.168.142.0 to 192.168.142.63
-✅ Devices active: ~64 hosts detected as up
-🔐 Common result: Most hosts had filtered or closed ports
-⚠️ Interesting host: 192.168.142.44

##Open ports:

-8001/tcp → vcom-tunnel
-8002/tcp → teradataordbms
-8080/tcp → http-proxy
-32768-32771/tcp → RPC-related ports

These open ports may expose services or entry points if not secured

##🧠 Key Learnings

-Understood how to perform TCP SYN scans with Nmap
-Learned about IP addressing, port filtering, and host discovery
-Practiced saving and reading scan output
-Identified what open ports might reveal about network vulnerability
-Got introduced to network enumeration, an essential part of cybersecurity


##📁 Files in This Repository

File	Description
-scan_results.txt	Raw output from Nmap command
-README.md	This documentation file


##❗ Important Note

⚠️ This scan was performed in a local private network (192.168.x.x). No sensitive data, credentials, or internet-facing systems are exposed. This project is for educational and internship purposes only.

##✅ Conclusion

-This task helped me build foundational skills in network reconnaissance — including host discovery, port scanning, and risk analysis. It serves as the first step into practical cybersecurity and ethical hacking.

