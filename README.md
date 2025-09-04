# Incident Handler's Journal  

This journal demonstrates my ability to **document, analyze, and respond to cybersecurity incidents** in a structured and professional way.  
It highlights my practical use of tools like **VirusTotal, Suricata, SIEMs, vulnerability scanners, and log analysis** to investigate threats and apply incident response playbooks.  

---

## Date: July 20, 2025  
### Entry: 1  

| Section        | Details |
|----------------|---------|
| **Description** | Documented a phishing incident that targeted employees of a mid-sized marketing firm. The suspicious email contained a link to a credential-stealing site. The SOC detected abnormal login attempts shortly after the email was opened, prompting an immediate investigation. Employee accounts were temporarily locked to prevent further compromise. |
| **Tool(s) used** | Email filtering logs, SIEM alerts |
| **The 5 W’s** | **Who:** An organized group of unethical hackers<br>**What:** Ransomware security incident<br>**When:** Tuesday morning at ~9:00 a.m.<br>**Where:** Small healthcare clinic in the United States<br>**Why:** Attackers exploited phishing emails to install malware, encrypt files, and demand ransom |
| **Additional Notes** | How could the healthcare company prevent this from happening again?<br>Should the company pay the ransom? |

---

## Date: August 3, 2025  
### Entry: 2  

| Section        | Details |
|----------------|---------|
| **Description** | Investigating an alert about a suspicious file being downloaded. |
| **Tool(s) used** | VirusTotal (used to analyze a file hash, confirmed as malicious) |
| **The 5 W’s** | **Who:** An organized group of unethical hackers<br>**What:** Malicious file downloaded<br>**When:**<br>- 1:11 p.m. → Employee receives malicious email<br>- 1:13 p.m. → Employee downloads file<br>- 1:15 p.m. → Unauthorized executables created<br>- 1:20 p.m. → IDS detects and alerts SOC<br>**Where:** Financial service company<br>**Why:** Lack of cybersecurity awareness |
| **Additional Notes** | File contained multiple viruses that steal credentials and sensitive information. |

---

## Date: August 6, 2025  
### Entry: 3  

| Section        | Details |
|----------------|---------|
| **Description** | Using a playbook to respond to a phishing incident. |
| **Tool(s) used** | None |
| **The 5 W’s** | **Who:** Malicious hacker<br>**What:** Sent a file with malware<br>**When:** July 20, 2022, 09:30:14 AM<br>**Where:** Financial service company<br>**Why:** Exploiting phishing to deliver malware |
| **Additional Notes** | Sender’s email and display name did not match, confirming spoofing. |

---

## Date: August 8, 2025  
### Entry: 4  

| Section        | Details |
|----------------|---------|
| **Description** | Used vulnerability scanning tools to assess a retail company’s web application security. Identified outdated plugins and misconfigured access controls. Results informed remediation and penetration testing. |
| **Tool(s) used** | Web server log analysis tools, Vulnerability scanning tools |
| **The 5 W’s** | **Who:** Unidentified attacker<br>**What:** Forced browsing attack exposing ~50,000 customer PII and financial records<br>**When:**<br>- Dec 22, 2022, 3:13 p.m. PT → Suspicious activity<br>- Dec 28, 2022, 7:20 p.m. PT → Breach confirmed<br>**Where:** Retail company’s e-commerce web application<br>**Why:** Weak access controls allowed attackers to manipulate order numbers in URLs |
| **Additional Notes** | Breach disclosed to customers; identity protection offered.<br>**Future Prevention:** Routine scans, penetration testing, stricter access controls. |

---

## Date: August 13, 2025  
### Entry: 5  

| Section        | Details |
|----------------|---------|
| **Description** | Explored Suricata to analyze network traffic and create intrusion detection signatures. Focused on monitoring suspicious patterns and generating alerts. |
| **Tool(s) used** | Suricata (log analysis, custom rules, traffic monitoring) |
| **The 5 W’s** | **Who:** N/A<br>**What:** N/A<br>**When:** N/A<br>**Where:** N/A<br>**Why:** N/A |
| **Additional Notes** | Regular log reviews and updated signatures are essential for IDS effectiveness. |

---

# Reflections / Notes  

- Systematic documentation helps identify recurring threats and patterns.  
- Tools applied: **VirusTotal, Suricata, SIEM, vulnerability scanners, log analysis**.  
- Using the **5 W’s** ensures full visibility into each incident.  
- **Prevention and awareness** (phishing training, vulnerability management, monitoring) reduce risks.  
- Reviewing past incidents highlights **policy and procedure gaps**, guiding future improvements.  
- Keeping detailed notes strengthens the **incident response workflow** and continuous learning.  
