# Vulnerable Services & Exploitable Network Protocols

This repository documents the **most risky, vulnerable, and commonly exploited network services**
from a **security, SOC, and penetration‑testing perspective**.

The structure is **risk‑first and exploit‑driven**, inspired by:
- Exploit‑DB
- Metasploit Framework
- MITRE ATT&CK
- Real-world incident response


## 🎯 Goals
- Identify **high‑risk services** by design or misconfiguration
- Map services to **real exploits, CVEs, and attack techniques**
- Help SOC analysts, students, and pentesters **prioritize threats**
- Provide a **service‑agnostic vulnerability reference**


## 📂 Repository Structure

```

vulnerable-services/
├── 01-Services/
│   ├── SMB/
│   ├── RDP/
│   ├── NetBIOS/
│   ├── MS-RPC/
│   ├── FTP/
│   ├── Telnet/
│   ├── HTTP/
│   ├── SSH/
│   ├── Databases/
│   └── Various/
├── 02-Risk-Level/
│   ├── Critical/
│   ├── High/
│   ├── Moderate/
│   └── Legacy/
├── 03-Attack-Techniques/
│   ├── Lateral-Movement/
│   ├── Credential-Access/
│   ├── Reconnaissance/
│   └── Command-and-Control/
├── 04-Exploitation/
│   ├── Exploit-DB/
│   ├── Metasploit/
│   └── CVE-PoCs/
└── 05-Quick-Reference/
├── Common-Ports.md
├── Insecure-Protocols.md
└── SOC-Cheatsheet.md
```

## 🚨 High-Risk Services Covered

| Service | Port | Risk |
|------|------|------|
| SMB | 445 | Critical |
| RDP | 3389 | Critical |
| NetBIOS | 137–139 | Critical |
| MS-RPC | 135 | Critical |
| FTP | 21 | High |
| Telnet | 23 | High |
| HTTP | 80 | High |
| VNC | 5900 | High |
| SNMP | 161 | High |
| PPTP | 1723 | Legacy |
| TFTP | 69 | Legacy |
| Various | 8000–8888 | Contextual |

---

## ⚠️ Disclaimer
This repository is for **educational and defensive security purposes only**.
Do not exploit systems you do not own or have permission to test.

---

## 📌 Inspired By
- Exploit Database
- Metasploit Framework
- MITRE ATT&CK
- OWASP
