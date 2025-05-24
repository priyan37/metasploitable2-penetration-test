# Full-Scope Penetration Test – Metasploitable 2

This repository contains a full-scope, black-box penetration testing report against **Metasploitable 2** — a vulnerable Linux-based VM designed for practicing real-world exploitation.

---

## Report Overview

- **Author**: Priyadharshan Vadivel  
- **Date**: May 20–24, 2025  
- **Type**: Independent Black-box Assessment  
- **Target**: Metasploitable 2 (192.168.237.162)  
- **Methodology**: PTES (Penetration Testing Execution Standard)  
- **Tools Used**: Nmap, Netdiscover, Enum4linux, Metasploit, Bash

---

## Report Contents

- ✅ Reconnaissance (Netdiscover, Ping)
- ✅ Scanning & Enumeration (Nmap, Enum4linux)
- ✅ Exploitation (CVE-2011-2523 – vsftpd 2.3.4)
- ✅ Post-Exploitation (Persistence, Data Extraction)
- ✅ Risk Ratings & CVSS
- ✅ Remediation Recommendations

📄 **Read the full report:**  
[👉 Penetration_Test_on_Metasploitable_2.pdf](./Penetration_Test_on_Metasploitable_2.pdf)

---

## Key Finding

- **Vulnerability**: vsftpd 2.3.4 backdoor  
- **CVE**: CVE-2011-2523  
- **Severity**: Critical (CVSS 10.0)  
- **Impact**: Remote root shell access without authentication

---

## Screenshots

All supporting images used in the report can be found under the `/images/` directory:

---

## Disclaimer

This assessment was conducted in a controlled lab environment for educational and ethical purposes only.  
No real-world systems were harmed or accessed during this test.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

