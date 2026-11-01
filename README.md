# 🔐 OPERATION SWEET SECRET
### Red Team vs Blue Team | Cybersecurity Capstone Project

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-blue)
![Project](https://img.shields.io/badge/Project-Red%20Team%20%7C%20Blue%20Team-red)
![Focus](https://img.shields.io/badge/Focus-Ethical%20Hacking%20%7C%20SOC%20Analysis-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Environment](https://img.shields.io/badge/Environment-Controlled%20Lab-orange)

**Operation Sweet Secret** is a controlled Red Team and Blue Team cybersecurity simulation developed as part of the TechCrush Ethical Hacking Cohort 7 Capstone Project.

The project demonstrates how attackers can exploit publicly available information, social engineering, endpoint vulnerabilities and inadequate security controls to compromise sensitive organisational information.

The engagement also demonstrates how defenders can identify security weaknesses, investigate Indicators of Compromise (IoCs), strengthen endpoint protection, improve network security and implement effective backup and recovery strategies.

The simulated target organisation, **COCA MOKA**, was used to demonstrate a multi-stage attack against its most valuable intellectual property: a confidential beverage recipe.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Project Objectives](#-project-objectives)
- [Project Scope](#-project-scope)
- [Laboratory Environment](#-laboratory-environment)
- [Tools and Technologies](#-tools-and-technologies)
- [Project Methodology](#-project-methodology)
- [Phase 1: Reconnaissance and Social Engineering](#-phase-1-reconnaissance-and-social-engineering)
- [Phase 2: Remote Access and Data Exfiltration](#-phase-2-remote-access-and-data-exfiltration)
- [Phase 3: Ransomware Simulation](#-phase-3-ransomware-simulation)
- [Phase 4: Blue Team Defensive Remediation](#-phase-4-blue-team-defensive-remediation)
- [Key Findings](#-key-findings)
- [Indicators of Compromise](#-indicators-of-compromise-iocs)
- [Security Recommendations](#-security-recommendations)
- [Screenshots and Evidence](#-screenshots-and-evidence)
- [Skills Demonstrated](#-skills-demonstrated)
- [Project Limitations](#-project-limitations)
- [Ethical Disclaimer](#-ethical-disclaimer)
- [Project Team](#-project-team)
- [Conclusion](#-conclusion)

---

## 🎯 Project Overview

| Project Information | Details |
|---|---|
| Project Name | Operation Sweet Secret |
| Organisation | COCA MOKA (Simulated Organisation) |
| Programme | TechCrush Ethical Hacking Cohort 7 |
| Project Type | Red Team / Blue Team Simulation |
| Project Category | Ethical Hacking and Defensive Security |
| Project Date | July 2026 |
| Environment | Controlled Virtual Lab |
| Primary Focus | Attack Simulation and Defensive Remediation |

The project was divided into four major phases:

1. Reconnaissance and Social Engineering.
2. Remote Access and Data Exfiltration.
3. Ransomware Impact Simulation and Recovery.
4. Blue Team Defensive Remediation.

The primary objective was to demonstrate how a targeted cyberattack could progress from information gathering to endpoint compromise, sensitive data theft and simulated ransomware impact.

The defensive component examined how the attack could be detected, prevented and recovered from using appropriate cybersecurity controls.

---

## 🎯 Project Objectives

The project aimed to:

- Conduct Open-Source Intelligence (OSINT) investigations against a simulated organisation.
- Identify publicly exposed information and potential attack surfaces.
- Perform network reconnaissance and service enumeration.
- Demonstrate a controlled spear-phishing scenario.
- Simulate remote endpoint compromise in an authorised laboratory.
- Demonstrate file discovery, staging and controlled data exfiltration.
- Simulate ransomware behaviour using reversible file encoding.
- Identify security weaknesses and potential Indicators of Compromise.
- Recommend endpoint, identity, network and data protection controls.
- Develop a defensive remediation strategy aligned with SOC operations.

---

## 🛡️ Project Scope

The engagement focused on the following security areas:

| Security Area | Activities |
|---|---|
| OSINT | Public information gathering and social media profiling |
| Reconnaissance | DNS enumeration, subdomain discovery and port scanning |
| Social Engineering | Spear-phishing scenario |
| Endpoint Security | Remote access and endpoint activity simulation |
| Data Security | Sensitive file discovery and controlled exfiltration |
| Ransomware | Reversible file encoding and restoration |
| Blue Team | IoC identification and defensive control recommendations |
| Recovery | Windows System Protection and automated restore points |

All activities were performed within the authorised academic simulation environment.

---

## 💻 Laboratory Environment

The project used a controlled virtual laboratory involving Windows and Linux systems.

**Environment components:**

- Windows-based simulated corporate endpoint.
- Linux-based attacker laboratory.
- Remote access simulation environment.
- Command-line and PowerShell administration.
- Network reconnaissance utilities.
- Controlled file transfer environment.
- Windows System Protection and Task Scheduler.

The infrastructure was designed to demonstrate attack and defence scenarios without compromising real organisations or production systems.

---

## 🧰 Tools and Technologies

### Tools used in the practical simulation

| Tool | Purpose |
|---|---|
| Blackbird | Cross-platform username enumeration for OSINT |
| Google Dorking | Search-engine-based information gathering |
| Subfinder | Passive subdomain enumeration |
| Nmap | Network scanning, port discovery and service identification |
| nslookup | DNS information gathering |
| dig | DNS record investigation |
| Celesty File Binder | Payload embedding in the simulated phishing attachment |
| Windows PowerShell | Remote command execution, file discovery and compression |
| Pinggy.io | Reverse tunnelling for the simulated data transfer |
| Windows Task Scheduler | Automated system restore point creation |

### Defensive technologies and controls examined

| Technology | Defensive Purpose |
|---|---|
| SPF, DKIM and DMARC | Email authentication and phishing protection |
| Windows Defender Controlled Folder Access | Protection against unauthorised file modifications |
| AppLocker | Application and script execution control |
| Snort | Network intrusion detection and prevention |
| Suricata | Network threat detection and traffic analysis |
| EDR | Endpoint threat detection and response |
| DLP | Data loss prevention |
| SIEM | Centralised security logging and event correlation |
| MFA | Stronger identity and authentication security |
| PAM | Privileged access management |

**Note:** The second table contains defensive technologies and controls evaluated or recommended in the report. It does not imply that every technology was installed or deployed during the practical exercise.

---

## 🔬 Project Methodology

The project followed a structured, four-phase Red Team and Blue Team methodology.

### Phase 1: Reconnaissance and Social Engineering

**Objective:** Identify publicly available information and develop an understanding of the organisation's potential attack surface.

Practical activities:

1. Conducted Google Dorking to identify publicly indexed information.
2. Used Blackbird for username enumeration across online platforms.
3. Performed manual verification of identified social media accounts.
4. Investigated publicly available organisational information.
5. Used DNS utilities to examine domain infrastructure.
6. Used Subfinder for passive subdomain enumeration.
7. Conducted Nmap scanning to identify exposed ports and services.
8. Developed a simulated spear-phishing scenario using OSINT-derived context.

**Key findings:**

- Publicly available employee information could be used to construct convincing phishing scenarios.
- The organisation's infrastructure exposed multiple web service ports.
- Google Dorking did not return relevant social media profiles, while Blackbird identified potential accounts for manual verification.
- The simulated spear-phishing scenario demonstrated the risks associated with excessive public information.

**Blue Team recommendations:**

- Implement SPF, DKIM and DMARC.
- Introduce external email warning banners.
- Conduct regular security awareness training.
- Apply an OSINT minimisation policy.
- Implement email attachment sandboxing.

---

### Phase 2: Remote Access and Data Exfiltration

**Objective:** Demonstrate how endpoint compromise could lead to unauthorised access to sensitive organisational information.

Practical activities:

1. Executed the authorised remote access simulation.
2. Established a remote session with the simulated Windows endpoint.
3. Used PowerShell to inspect system information and file directories.
4. Performed recursive file discovery to locate the simulated confidential recipe.
5. Compressed the target directory into a ZIP archive.
6. Demonstrated controlled transfer through a reverse tunnelling service.
7. Verified receipt and accessibility of the transferred archive.

**Key findings:**

- Remote access enabled interaction with the simulated endpoint.
- Sensitive files could be discovered through recursive directory searches.
- File compression provided a staging mechanism before transfer.
- Outbound tunnelled connections could create data exfiltration opportunities.

**Blue Team recommendations:**

- Enable Windows Object Access Auditing.
- Monitor Windows Security Event ID 4663.
- Implement Data Loss Prevention (DLP).
- Encrypt sensitive information at rest.
- Monitor unusual outbound connections.
- Apply the Principle of Least Privilege.
- Investigate unexpected archive creation and transfers.

---

### Phase 3: Ransomware Simulation and Recovery

**Objective:** Demonstrate the potential impact of ransomware on endpoint availability and validate file recovery.

Practical activities:

1. Executed a controlled PowerShell-based ransomware simulation.
2. Restricted the target scope to designated desktop files.
3. Converted file contents into reversible Base64-encoded data.
4. Renamed affected files using the `.locked` extension.
5. Created a simulated ransom demand note.
6. Executed the restoration script.
7. Recovered the original file contents.
8. Verified successful access to the restored recipe file.

**Key findings:**

- Mass file modification can disrupt access to important information.
- Unusual file-extension changes can serve as behavioural detection signals.
- Ransom notes can provide an additional indicator of ransomware activity.
- A tested recovery process can restore affected data without paying a ransom.

**Important technical clarification:** This was a reversible Base64 encoding simulation, not genuine cryptographic ransomware. No irreversible encryption was performed.

**Blue Team recommendations:**

- Deploy Endpoint Detection and Response (EDR).
- Enable Windows Controlled Folder Access.
- Implement application whitelisting.
- Introduce ransomware canary files.
- Maintain a 3-2-1 backup strategy.
- Test restoration procedures regularly.

---

### Phase 4: Blue Team Defensive Remediation

**Objective:** Develop a layered security architecture addressing the weaknesses demonstrated during the offensive simulation.

The defensive remediation strategy focused on four main pillars.

**1. Identity Governance**

- Enforce Multi-Factor Authentication.
- Apply the Principle of Least Privilege.
- Introduce Privileged Access Management.
- Monitor privileged account activities.

**2. Host Hardening and Endpoint Protection**

- Implement AppLocker.
- Enable Controlled Folder Access.
- Deploy behavioural EDR monitoring.
- Restrict unauthorised application execution.

**3. System Restoration and Backup**

- Enable Windows System Protection.
- Configure automated restore points using Task Scheduler.
- Maintain secure backups.
- Validate restoration procedures.

**4. Network Segmentation and Monitoring**

- Isolate sensitive intellectual property within a protected network segment.
- Apply Next-Generation Firewall access restrictions.
- Monitor suspicious outbound traffic.
- Introduce IDS/IPS monitoring using Snort or Suricata.
- Detect suspicious tunnelling and data transfer activity.

---

## 🔎 Key Findings

The simulation identified several important security weaknesses.

| Finding | Security Impact | Recommended Control |
|---|---|---|
| Excessive public information | Increased social engineering risk | OSINT minimisation |
| Weak phishing resistance | Potential endpoint compromise | Email security and awareness training |
| Exposed web services | Expanded attack surface | Firewall restrictions and service hardening |
| Excessive endpoint privileges | Increased compromise impact | Least Privilege and PAM |
| Insufficient file access monitoring | Delayed detection of sensitive file access | Windows Object Access Auditing |
| Unmonitored outbound transfers | Potential data exfiltration | DLP and IDS/IPS |
| Weak endpoint protection | Increased ransomware risk | EDR and Controlled Folder Access |
| Inadequate recovery readiness | Potential prolonged business disruption | Tested backups and restore points |

---

## 🚨 Indicators of Compromise (IoCs)

The following indicators were identified as useful detection opportunities during the simulated attack.

| Attack Activity | Potential Indicator | Defensive Monitoring |
|---|---|---|
| Spear-phishing | Suspicious external email and attachment | Email security monitoring |
| Initial compromise | Unexpected executable launched by a document reader | EDR process monitoring |
| File discovery | Unusual access to sensitive directories | Windows Event ID 4663 |
| File staging | Unexpected archive creation | Endpoint and PowerShell logging |
| Data exfiltration | Unusual outbound HTTPS POST traffic | Network monitoring and DLP |
| Reverse tunnelling | Unexpected SSH tunnelling over port 443 | IDS/IPS monitoring |
| Ransomware simulation | Rapid file modifications and `.locked` extensions | EDR behavioural detection |
| Ransom note creation | Unexpected ransom note text file | Endpoint file monitoring |

These are potential detection signals derived from the simulated activities, not confirmed alerts from a production SIEM.

---

## 📸 Screenshots and Evidence

This repository includes practical evidence organised according to the four project phases.

### 1. Reconnaissance and OSINT

Store screenshots demonstrating:

- Blackbird username enumeration.
- Social media account discovery.
- Nmap port scanning.
- Service identification.
- Network reconnaissance observations.

### 2. Phishing and Remote Access

Store screenshots demonstrating:

- Simulated phishing email.
- Remote access session.
- Remote endpoint monitoring.
- System information discovery.

### 3. Data Exfiltration

Store screenshots demonstrating:

- PowerShell file discovery.
- ZIP archive creation.
- Tunnel establishment.
- Successful transfer confirmation.
- Verification of the transferred archive.

### 4. Ransomware Simulation

Store screenshots demonstrating:

- Files renamed with `.locked` extensions.
- Simulated ransom note.
- Encoded file contents.
- Successful file restoration.

### 5. Blue Team Defence and Recovery

Store screenshots demonstrating:

- Windows System Protection enabled.
- Task Scheduler configuration.
- Automated restore point creation.
- Successful recovery verification.

---

## 🎓 Skills Demonstrated

This capstone project demonstrates practical exposure to several cybersecurity domains.

**Offensive Security**

- Open-Source Intelligence (OSINT).
- Digital footprint analysis.
- Network reconnaissance.
- Port and service enumeration.
- Social engineering simulation.
- Endpoint compromise simulation.
- PowerShell administration.
- Data exfiltration simulation.
- Ransomware behaviour simulation.

**Defensive Security and SOC Operations**

- Security event identification.
- Indicators of Compromise (IoCs).
- Endpoint threat monitoring concepts.
- Windows event auditing.
- Network traffic monitoring concepts.
- Data Loss Prevention (DLP).
- Incident prevention and remediation.
- Backup and recovery planning.
- Security architecture and hardening.

**Technical Skills**

- Windows administration.
- Linux command-line operations.
- PowerShell.
- Nmap.
- DNS investigation.
- Security documentation.
- Technical reporting.
- Risk identification and mitigation.

---

## ⚠️ Project Limitations

This was an academic simulation and not a production penetration test or live SOC deployment.

The following limitations apply:

- The target organisation was simulated.
- All attack activities were conducted in a controlled environment.
- The ransomware demonstration used reversible Base64 encoding rather than genuine encryption.
- The project did not document a production SIEM deployment or live SOC alert investigation.
- Defensive controls such as Snort, Suricata, EDR and DLP were evaluated as recommendations rather than verified production implementations.

---

## ⚖️ Ethical Disclaimer

This project was conducted exclusively for educational purposes as part of the TechCrush Ethical Hacking Cohort 7 capstone programme.

All attack scenarios were performed within authorised virtual laboratory environments.

No real organisation, production network or individual was intentionally compromised.

The techniques and findings documented in this repository are intended to support cybersecurity education, defensive security awareness and ethical hacking practice.

**Do not reproduce these activities against systems or networks without explicit authorisation.**

---

## 👥 Project Team

**TechCrush Ethical Hacking Cohort 7 – Capstone Group One**

- David Usibe – Group Lead
- Akintunde Qudus Adeola
- Beckley Daniel
- Isaiah Udo
- Samuel Oladipo
- Opeyemi Daniel Afuwajomo
- Umar Musa Saidu
- Muhammad Haruna Osori
- Dawodu Ayobami
- Iheanyichukwu Daniel
- Ndu Okolie

---

## 🏁 Conclusion

Operation Sweet Secret demonstrated how a targeted cyberattack could progress from publicly available intelligence gathering to endpoint compromise, sensitive data exfiltration and simulated ransomware impact.

The project also highlighted the importance of layered security controls, effective endpoint monitoring, identity governance, network segmentation and reliable backup strategies.

Most importantly, the engagement established a relationship between offensive attack techniques and defensive security measures, showing how each attack stage presents opportunities for detection, prevention and recovery.

This project strengthened our practical understanding of ethical hacking and defensive cybersecurity while providing a foundation for further development in Security Operations Centre (SOC) analysis, threat detection and incident response.
operation-sweet-secret/
│
├── README.md
│
├── docs/
│   ├── project-report.pdf
│   └── Operation_Sweet_Secret_SOC_Portfolio_Deliverables.pdf
│
├── deliverables/
│   ├── soc-investigation.md
│   ├── ioc-detection-mapping.md
│   └── incident-response-report.md
│
├── screenshots/
│   ├── reconnaissance/
│   ├── phishing/
│   ├── data-exfiltration/
│   ├── ransomware/
│   └── blue-team-defence/
│
└── findings/
    └── defensive-recommendations.md
---

**Project:** Operation Sweet Secret  
**Programme:** TechCrush Ethical Hacking Cohort 7  
**Date:** July 2026  
**Category:** Cybersecurity | Red Team | Blue Team | SOC Analyst Portfolio
