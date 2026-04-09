# Kanhay Thakore 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/kanhaythakore/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail)](mailto:thakorekanhay70@gmail.com)

## 👨‍💻 About Me

System-focused engineer with experience in network security, system validation, SOC and detection engineering. 

Built multi-node environments to simulate real-world scenarios, execute test cases, and analyze system behavior using logs and packet data. Strong foundation in networking, security concepts, and Python-based automation.

Experienced in SIEM, intrusion detection, vulnerability assessment, and penetration testing with a focus on validating system performance, reliability, and security.

## 🎓 Certifications

```text
🔐 CompTIA Security+        ✓ Certified            
🛡️ Let's Defend SOC Analyst Path ✓ Certified
🐍 Python for Everybody ✓ Certified
📊 Python Data Structures & Machine Learning ✓ Certified
```
**🎯 Pursuing:** Cisco CCNA & CompTIA CYSA+

## 🛠️ Technical Skills

### 🔵 SIEM & Log Analysis
- **Platforms:** Wazuh 4.x, ELK Stack (Kibana), OpenSearch Dashboard
- **Log Sources:** Windows Event Logs (4624/4625/4672/5379), Sysmon, Firewall Logs, DNS Query Logs, SSL/TLS Traffic, Zeek Network Telemetry
- **Capabilities:** Multi-source log ingestion, real-time alert triage, cross-host event correlation, IOC-based querying, attack timeline reconstruction

### 🚨 Intrusion Detection & Threat Monitoring
- **Tools:** Snort IDS 2.9.x, KFSensor Honeypot, Wazuh FIM
- **Skills:** Custom Snort rule authoring, OSSEC integration, honeypot deployment & traffic capture, real-time hash-based File Integrity Monitoring (MD5/SHA256), DoS pattern recognition

### 🔍 Digital Forensics & Incident Response (DFIR)
- **Tools:** Volatility 3, DumpIt, Wireshark, Kibana, DFIR-IRIS
- **Skills:** Live memory acquisition & RAM analysis (pslist, netscan), network artifact recovery, process injection detection, multi-phase breach timeline reconstruction, IOC extraction & documentation
- **Framework:** NIST SP 800-61 incident response lifecycle

### 🛡️ Vulnerability Management
- **Tools:** Nessus (credentialed & non-credentialed scans), MegaPing (IP/Port/NetBIOS/Share/Security Scanner)
- **Skills:** CVSS & VPR-based prioritization, false positive analysis, remediation report writing, asset inventory across multi-subnet environments, remote port monitoring

### 🌐 Network Security & Traffic Analysis
- **Tools:** Wireshark, Zeek (Bro), tcpdump, Nmap, hping3
- **Skills:** Packet-level protocol analysis, DNS tunneling detection, TCP/IP & UDP traffic inspection, port scanning (SYN/TCP/UDP), SYN flood simulation & detection, network segmentation design

### ⚙️ Scripting & Automation
- **Languages:** Python, PowerShell, Bash
- **Applied:** Security workflow automation, log parsing, alert scripting, Google Sheets API integration

## 🚀 Featured Projects

### [Incident Response & Detection Architecture](https://github.com/Kanhay-Thakore/Incident-Response-Detection-Architecture)
**Enterprise-Grade SIEM Implementation with Multi-Vector Threat Detection**

**Full-stack Security Operations Center for CSA271.com combining Wazuh SIEM, Snort IDS, and Volatility for comprehensive threat detection, log correlation, and forensic analysis across multi-OS infrastructure.**

**Key Achievements:**
- 🎯 **100% detection rate** - All 4 attack vectors successfully detected (Brute Force, SYN/TCP/UDP Scans)
- ⚡ **Real-time correlation** - Zero-latency log forwarding from agents to SIEM
- 🔍 **Memory forensics** - Full RAM analysis with network artifact recovery
- 🛡️ **Active FIM** - Real-time hash-based file integrity monitoring
- 🌐 **Multi-OS deployment** - Windows Server, Ubuntu, Kali Linux integration

**Tech Stack:** Wazuh SIEM | Snort IDS | Volatility 3 | DumpIt | Windows Server 2016 | Ubuntu 20.04 | Kali Linux | VMware

[View Project →](https://github.com/Kanhay-Thakore/Incident-Response-Detection-Architecture)

---

### [Post Incident Log Analysis — S1P3](https://github.com/Kanhay-Thakore/Post-Incident-Log-Analysis)
**DFIR Investigation using Kibana & MITRE ATT&CK Framework**

**Full post-incident forensic investigation of a confirmed security breach recorded on March 20, 2023, analyzing security logs from multiple compromised Windows hosts using Kibana (ELK Stack) and mapping all detected activity to the MITRE ATT&CK Windows Matrix.**

**Key Achievements:**
- 🗺️ **20+ MITRE techniques mapped** - Full attack progression across 8 distinct ATT&CK tactics
- 🔍 **Multi-phase intrusion traced** - Credential theft → Privilege escalation → C2 → Exfiltration
- ⏱️ **4-hour attack timeline reconstructed** - Chronological correlation across 5 compromised hosts
- 🚨 **HIGH → CRITICAL severity confirmed** - Brute-force login, process injection, DNS tunneling validated
- 🧠 **15 suspicious event categories documented** - Each with log evidence and MITRE mapping

**Tech Stack:** Kibana / ELK Stack | Winlogbeat | MITRE ATT&CK | DFIR-IRIS | Windows Event Logs | DNS & SSL Log Analysis

[View Project →](https://github.com/Kanhay-Thakore/Post-Incident-Log-Analysis)

## Featured SOC Cases — LetsDefend SOC Analyst Path
Built hands-on SOC analyst skills through the LetsDefend pathway, including SIEM alert triage, log analysis, phishing and email header investigation, malware and ransomware analysis, IOC validation, command-and-control tracking, endpoint investigation, false-positive identification, incident containment, escalation, and clear case documentation aligned to real-world SOC workflows.

- [SOC109 – Emotet Malware Detected](./SOC109%20-%20Emotet%20Malware%20Detected.md): Investigated a high-severity Emotet alert, validated malicious indicators, and confirmed the endpoint was protected before compromise.
- [SOC145 – Ransomware Detected](./SOC145%20-%20Ransomware%20Detected.md): Analyzed ransomware activity, confirmed host compromise, and supported containment and escalation actions. 
- [SOC146 – Phishing Mail Analysis: Excel 4.0 Macros Attack](./SOC146%20-%20Phishing%20Mail%20Analysis%20Excel%204.0%20Macros%20Attack.md): Investigated a malicious phishing email with Excel 4.0 macros, traced payload execution, and identified C2-related activity.
- [SOC168 – Whoami Command Detected in Request Body](./SOC168%20-%20Whoami%20Command%20Detected%20in%20Request%20Body.md): Investigated a web command injection attempt, verified successful command execution, and escalated after isolating the affected server.


## 🔧 Technologies
```text
SIEM & Log Analysis      ████████████████████░  95%
Intrusion Detection      ███████████████████░░  90%
Incident Response        ██████████████████░░░  85%
Digital Forensics        ████████████████░░░░░  80%
Vulnerability Management ███████████████░░░░░░  75%
Python & Automation      ██████████████░░░░░░░  70%
```
## 📫 Let's Connect

Open to opportunities in **(SOC) Analyst** | **Incident Response** | **Cybersecurity Analyst** | **Information Security Analyst** | **Network Testing** | **System Validation** | **Product Verification** | **Security Engineering**

- 💼 LinkedIn: [Connect with me](https://www.linkedin.com/in/kanhaythakore/)
- 📧 Email: thakorekanhay70@gmail.com

---

*"Building the future of automated security operations, one detection at a time."*
