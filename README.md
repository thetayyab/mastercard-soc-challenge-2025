# Mastercard SOC Challenge 2025  
## End-to-End SOC Incident Response & PCAP Forensic Investigation

This project documents a full-scale Security Operations Center (SOC) investigation conducted by analyzing raw PCAP network traffic from a simulated real-world intrusion.

---

## 🔍 Investigation Overview

The attack chain reconstructed during analysis:

1. Phishing email delivery with malicious Excel macro (book1.xlsm)
2. PowerShell payload execution (BENlGN.docx.ps1)
3. Command-and-Control (C2) communication
4. Encrypted ZIP retrieval (flag.zip)
5. Post-exploitation system enumeration
6. Suspicious outbound TLS traffic analysis

---

## 🛠 Tools Used

- Wireshark
- Tshark
- Kali Linux
- CyberChef
- Python
- xxd
- Base85 decoding

---

## 🧠 Skills Demonstrated

- Network Forensics (PCAP Analysis)
- Incident Response
- Threat Hunting
- IOC Extraction
- MITRE ATT&CK Mapping
- Malware Analysis
- PowerShell & Macro Investigation

---

## 🎯 Key Findings

- Identified phishing-based initial infection vector.
- Extracted and decoded ASCII85-obfuscated password.
- Validated SHA256 hash of malicious payload.
- Detected remote command execution (whoami, net user, query user).
- Analyzed suspicious outbound TLS communication.

---

## 📄 Full Investigation Report

See detailed PDF report in this repository.
