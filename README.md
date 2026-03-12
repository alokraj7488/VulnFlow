# VulnFlow: 10-in-1 Vulnerability Scanner

A lightweight, all-in-one CLI tool that integrates 10 essential security scanners for fast reconnaissance and vulnerability assessment.

---

## 🔧 Included Tools
1. **Nmap** – Network & service discovery  
2. **Nikto** – Web server vulnerabilities  
3. **Gobuster** – Directory brute-forcing  
4. **Whois** – Domain registration info  
5. **nslookup** – DNS lookups  
6. **Wafw00f** – WAF detection  
7. **SSLScan** – SSL/TLS analysis  
8. **WhatWeb** – Tech stack fingerprinting  
9. **SQLMap** – SQL injection (safe crawl mode)  
10. **Nessus** – Integration stub  

➕ **Run all tools at once** for a full audit with a consolidated report.

---

## 🚀 Quick Start

### Prerequisites (Kali/Ubuntu):
sudo apt install -y nmap nikto gobuster whois dnsutils wafw00f sslscan whatweb sqlmap

**Gobuster** uses /usr/share/wordlists/dirb/common.txt – install seclists or adjust path if needed.
## Run
1. git clone https://github.com/alokraj7488/VulnFlow.git  
2. cd vuln-suite 
3. python3 main.py  

⚠️ **Important**  
- For authorized testing only.  
- SQLMap runs in non-intrusive mode (`--batch --crawl=1`).  
- Each scan times out after 10 minutes.  
- Use responsibly and legally.

Educational use only. Author not liable for misuse.
