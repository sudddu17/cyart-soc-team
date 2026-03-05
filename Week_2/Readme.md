CYART SOC TEAM – Week 2
Security Operations Center (SOC) – Alert to Response Workflow

Overview
This repository documents Week-2 SOC activities, covering alert prioritization, incident classification, triage, evidence collection, response actions, and reporting. The objective is to demonstrate a complete Alert → Detection → Response → Reporting cycle using industry-standard SOC tools.

---

Repository Structure
cyart-soc-team/
 └── Week 2/
     ├── Week_2_SOC_Detailed_Report.pdf
     ├── README.md
     ├── Screenshots/
     │    ├── Wazuh_Alerts_Severity.png
     │    ├── CVSS_Scoring_Google_Sheets.png
     │    ├── TheHive_Incident_Ticket.png
     │    ├── Velociraptor_Evidence_Collection.png
     │    └── Metasploit_Wazuh_Detection.png
     └── Notes/

---

Tools Used
**Wazuh SIEM** – Alert detection, severity classification, dashboards  
**Google Sheets** – CVSS scoring and alert prioritization  
**TheHive** – Incident case management and escalation  
**Velociraptor** – Endpoint evidence collection  
**Metasploit Framework** – Attack simulation  
**VirusTotal / AlienVault OTX** – Threat intelligence validation  
**FTK Imager** – Evidence preservation  
**CrowdSec** – IP blocking and response (conceptual)

---

Alert Priority Levels

| Priority  | Description |
|----------|------------|
| Critical | Active exploitation, ransomware, root access |
| High     | Unauthorized access, privilege escalation |
| Medium   | Brute-force attempts, suspicious activity |
| Low      | Reconnaissance and scanning |

---

Step-by-Step SOC Workflow

1️⃣ Attack Simulation
- Exploited Metasploitable2 using Metasploit  
- Exploit used: `vsftpd_234_backdoor`

 2️⃣ Detection
- Wazuh detected suspicious FTP behavior
- Alert severity classified as **Critical**

3️⃣ Prioritization
- CVSS score calculated as **9.8**
- Priority assigned: **Critical**

4️⃣ Incident Triage
- Incident ticket created in TheHive
- Indicators of Compromise documented

5️⃣ Evidence Collection
- Volatile data collected using Velociraptor
- Network connections and memory artifacts preserved

6️⃣ Response
- Compromised system isolated
- Attacker IP blocked (conceptual CrowdSec action)

7️⃣ Reporting
- Incident documented using SANS Incident Response template
- Lessons learned recorded

---

🔁 Attack → Detection → Response Flow