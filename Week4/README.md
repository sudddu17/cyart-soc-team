\# 🔐 SOC Portfolio Project – End-to-End Incident Response



\## 📌 Overview

This project demonstrates a complete \*\*Security Operations Center (SOC)\*\* workflow, covering threat detection, analysis, response, automation, and reporting.



The objective of this project is to simulate real-world cyber attacks and showcase practical SOC skills aligned with \*\*MITRE ATT\&CK\*\* and \*\*NIST Incident Response Framework\*\*.



\---



\## 🚀 Key Features



\- 🔍 Threat Hunting (Hypothesis-driven)

\- ⚙️ SOAR Automation (Playbooks)

\- 🚨 Alert Triage \& Validation

\- 🧠 Root Cause Analysis (5 Whys)

\- 🎭 Adversary Emulation (MITRE Techniques)

\- 📊 SOC Metrics (MTTD, MTTR, Dwell Time)

\- 🛡️ Incident Response \& Containment

\- 📑 Executive Reporting



\---



\## 🛠️ Tools \& Technologies Used



\- SIEM: Wazuh / Elastic Security  

\- SOAR: Splunk Phantom / TheHive  

\- Threat Intelligence: AlienVault OTX, VirusTotal  

\- Adversary Emulation: MITRE Caldera  

\- Exploitation: Metasploit  

\- Forensics: Velociraptor, FTK Imager  



\---



\## 🔍 Threat Hunting Summary



\- Developed hypothesis: \*\*Unauthorized privilege escalation\*\*

\- Analyzed logs for \*\*Event ID 4672\*\*

\- Identified suspicious admin privilege assignment

\- Mapped to \*\*MITRE ATT\&CK: T1078 (Valid Accounts)\*\*



\---



\## ⚙️ SOAR Automation



A playbook was created to automate phishing response:



\- Check IP reputation  

\- Block malicious IP  

\- Create incident ticket in TheHive  



✅ Result: Reduced manual effort and faster response time



\---



\## 🚨 Alert Triage Process



\- Analyzed alerts from SIEM  

\- Validated file hash using VirusTotal  

\- Prioritized incidents based on severity  



\---



\## 🎭 Adversary Emulation



Simulated attacker techniques:



\- \*\*T1566 – Phishing\*\*

\- \*\*T1210 – Exploitation of Remote Services\*\*



📌 Outcome:

\- Detection successful for phishing  

\- Improvement needed in lateral movement detection  



\---



\## 🧠 Root Cause Analysis (RCA)



Used \*\*5 Whys Method\*\*:



\- User clicked phishing link  

\- Weak email filtering  

\- Misconfigured detection rules  



📌 Conclusion: Need stronger email security and monitoring



\---



\## 📊 SOC Metrics



| Metric | Value |

|-------|------|

| MTTD  | 2 Hours |

| MTTR  | 4 Hours |

| Dwell Time | 6 Hours |



\---



\## 🛡️ Incident Response Workflow



1\. Detection via SIEM  

2\. Alert triage  

3\. Threat validation  

4\. Containment (IP blocking, system isolation)  

5\. Automation via SOAR  

6\. Post-incident analysis  



\---



\## 💼 Skills Demonstrated



\- SOC Operations  

\- Threat Hunting  

\- Incident Response  

\- SIEM \& SOAR  

\- Cyber Threat Intelligence  

\- Security Automation  



\---



