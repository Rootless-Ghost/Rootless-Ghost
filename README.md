# Rootless-Ghost/RG-Nebula


<div align="center">
 
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=1000&color=9D1AF7&center=true&multiline=true&width=600&lines=Trained+for+chaos.+Built+for+defense.;Rootless.+Relentless.+Ready.;From+combat+zones+to+kill+chains.)](https://git.io/typing-svg)
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=1000&color=00D4FF&center=true&multiline=true&width=600&lines=I+break+it+to+understand+it.;I+defend+it+because+I+can.;The+work+speaks+when+I+don't.)](https://git.io/typing-svg)

Navy Veteran | SOC Analyst | Detection Engineering | Purple Team 

 </div>

 
###

![Chillin](chillin-S13-c.gif)



## 

![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%201%25-red?style=for-the-badge&logo=tryhackme)

[![TryHackMe Badge](https://tryhackme-badges.s3.amazonaws.com/RG.Nebula.png?v=10)](https://tryhackme.com/p/RG.Nebula)






[![Obsidian](https://img.shields.io/badge/Obsidian-483699?style=for-the-badge&logo=obsidian&logoColor=white)](https://obsidian.md/) [![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion) [![TCM Security](https://img.shields.io/badge/TCM_Security-Student-9D1AF7?style=for-the-badge)](https://tcm-sec.com/)



## About Me

**Former Navy Hospital Corpsman** to cybersecurity with real-world combat experience. I bring military discipline, high-pressure decision-making skills, and a systematic approach to threat detection and incident response.

Purple Team & SOC Focus — building both offensive and defensive capabilities                                                                                                                                
Operating a 22+ VM home lab for attack simulation and detection engineering  
Pursuing **PSAA → PSAP → Security+ → CCDL1 → PAPA → PJPT → PNPT** certification path  
**TryHackMe Top 1%** - 270+ rooms completed (Inactive)
Actively seeking **SOC Analyst & Purple Team** roles


## What I Do

**Red Team**
- Penetration Testing & Security Research
- Red team operations & exploitation
- Active Directory & Windows exploitation
- Network security & privilege escalation

**Blue Team**
- Threat detection & incident response
- SIEM analysis & log correlation
- Threat hunting & malware analysis
- Security monitoring & alerting

---
## Featured Projects

### Nebula Forge
All detection engineering and IR tools below are part of 
**[Nebula Forge](https://github.com/Rootless-Ghost/nebula-forge)** 
— an open-source SOC platform of **17 tools** covering the full workflow: 
Detect → Normalize → Hunt → Drift → Cluster → Simulate → Investigate → Respond → Report.

Nebula Forge includes two automated pipelines:
- **drift-scan** — scheduled Sigma rule drift analysis across your detection library
- **purple-loop** — end-to-end purple team cycle: simulate (AtomicLoop) → detect (Wazuh/Splunk) → validate (DriftWatch) | *Pipeline validated end-to-end April 2026*


### Detection Engineering
**[YaraForge](https://github.com/Rootless-Ghost/YaraForge)** - YARA Rule Generator & Testing Platform  
Build, manage, test, and visualize YARA detection rules with MITRE ATT&CK mapping and a detection dashboard.  
`Python` `Flask` `YARA` `MITRE ATT&CK` `Detection Engineering`

**[SnortForge](https://github.com/Rootless-Ghost/SnortForge)** - SnortForge - Snort IDS/IPS Rule Generator — Flask web app with multi-content chaining, Snort 2/3 syntax toggle, rule performance scoring, 12 detection templates, inline help tooltips, PCRE flag checkboxes, HTTP URI/Header matching, rule validation, and .rules file import/export. Dark-themed UI with real-time live preview. v1.2.0.
`Python` `Flask` `Snort` `IDS/IPS` `Network Security`

**[SigmaForge](https://github.com/Rootless-Ghost/SigmaForge)** — Vendor-Agnostic Sigma Rule Generator
Custom conversion engine (no pySigma dependency) generating Sigma rules to **6 SIEM backends**: Splunk SPL, Elastic KQL, EQL, Sentinel KQL, Wazuh XML, and QRadar AQL — plus Detection-as-Code JSON. MITRE ATT&CK mapping, 12 pre-built templates, rule library, and standalone CLI.
`Python` `Flask` `Sigma` `SIEM` `Detection Engineering` `CLI`

### Nebula Forge Detection Suite v2
 
**[LogNorm](https://github.com/Rootless-Ghost/LogNorm)** - Log Source Normalizer *(port 5006)*  
Normalizes log sources from disparate inputs into a consistent ECS-lite schema for downstream detection and analysis pipelines.  
`Python` `Flask` `Log Normalization` `ECS` `SIEM`
 
**[HuntForge](https://github.com/Rootless-Ghost/HuntForge)** - MITRE ATT&CK Hunt Playbook Generator *(port 5007)*  
Generates structured threat hunting playbooks mapped to MITRE ATT&CK techniques, providing analyst-ready queries and investigation checklists.  
`Python` `Flask` `MITRE ATT&CK` `Threat Hunting` `Detection Engineering`
 
**[DriftWatch](https://github.com/Rootless-Ghost/DriftWatch)** - Sigma Rule Drift Analyzer *(port 5008)*  
Analyzes Sigma rule libraries for drift — identifying stale, misconfigured, or coverage-gapped rules over time. Feeds the drift-scan pipeline.  
`Python` `Flask` `Sigma` `Detection Engineering` `Rule Management`
 
**[ClusterIQ](https://github.com/Rootless-Ghost/ClusterIQ)** - Contextual Alert Clustering Engine *(port 5009)*  
Groups and contextualizes alerts using behavioral clustering to reduce noise and surface high-fidelity incident signals for SOC triage.  
`Python` `Flask` `Alert Clustering` `SOC` `Incident Response`
 
**[AtomicLoop](https://github.com/Rootless-Ghost/AtomicLoop)**  — Atomic Red Team Test Runner (port 5011)
Executes Atomic Red Team tests in controlled loops for purple team validation, feeding results into the purple-loop pipeline for detection coverage measurement. Dedicated purple loop target: Win10x2 (Wazuh agent 005, AtomicLoop-Test).
`Python` `Flask` `Atomic Red Team` `Purple Team` `MITRE ATT&CK`

### Endpoint Security

**[EndpointForge](https://github.com/Rootless-Ghost/EndpointForge)** - Cross-Platform Endpoint Security Monitor  
Host-based intrusion detection and endpoint triage across 5 modules: process execution, file integrity (SHA-256 FIM), network connections, registry persistence (Windows), and autoruns — all MITRE ATT&CK mapped. Includes **Wazuh export integration**: `POST /api/wazuh/export` writes NDJSON picked up by the Wazuh agent using bundled decoder and rules (IDs 100200–100265) with ATT&CK technique tags — no manual log shipping. Markdown/JSON report generation for IR workflows.  
`Python` `Flask` `MITRE ATT&CK` `HIDS` `Endpoint Security` `Wazuh`
 
**[EndpointTriage](https://github.com/Rootless-Ghost/EndpointTriage)** - Windows Endpoint Forensic Artifact Collector  
Automated PowerShell-based IR triage script that collects volatile and non-volatile forensic artifacts — running processes with hashes, network connections, registry persistence checks, scheduled tasks, event log extraction (Security, Sysmon, PowerShell, Defender), named pipe enumeration, and suspicious indicator flagging. Outputs a structured triage package with HTML summary report.  
`PowerShell` `Incident Response` `Forensics` `DFIR` `Endpoint Security`

### Blue Team Operations

**[log-analyzer](https://github.com/Rootless-Ghost/log-analyzer)** - Security Log Analyzer  
Python-based log analysis tool designed for SOC analysts with pattern matching and anomaly detection.  
`Python` `Flask` `SIEM` `Log Analysis` `SOC`

**[phishing-analyzer](https://github.com/Rootless-Ghost/phishing-analyzer)** - Phishing Email Analyzer  
Email header and content analysis tool for identifying phishing campaigns and malicious indicators.  
`Python` `Email Security` `Phishing Detection` `Blue Team`

**[security-awareness-training](https://github.com/Rootless-Ghost/security-awareness-training)** - Security Awareness Platform  
Enterprise-style platform with phishing simulations, training modules, and progress tracking.  
`Python` `Flask` `Security Training` `Phishing Simulation`

### Threat Intelligence

**[Threat-intel-dashboard](https://github.com/Rootless-Ghost/Threat-intel-dashboard)** - Threat Intelligence Dashboard  
Real-time threat intelligence platform with IOC tracking, feed aggregation, and visual analytics for SOC operations.  
`HTML` `JavaScript` `Threat Intelligence` `OSINT` `SOC`

### Incident Response

**[SIREN](https://github.com/Rootless-Ghost/SIREN)** - Security Incident Response Engine & Notation  
Professional incident report generator following NIST 800-61 framework with severity scoring, IOC tracking, timeline management, and Markdown/JSON export.  
`Python` `Flask` `NIST 800-61` `Incident Response` `SOC`

### Wireless Security

**[Hidden-Rogue-AP-Detector](https://github.com/Rootless-Ghost/Hidden-Rogue-AP-Detector)** - Rogue Access Point Detector
Python-based wireless security tool for detecting unauthorized access points using RSSI signal strength analysis, whitelist management, and active/passive scanning modes.
`Python` `Scapy` `Wireless Security` `Network Monitoring` `Rogue AP Detection`

**[Wi-Fi-Probe-Request-Sniffer](https://github.com/Rootless-Ghost/Wi-Fi-Probe-Request-Sniffer)** - Wi-Fi Probe Request Analyzer
Captures and analyzes wireless probe requests from nearby devices with SSID extraction, MAC vendor identification, and CSV/JSON export for network visibility and device enumeration.
`Python` `Scapy` `802.11` `Network Security` `Device Enumeration`

---

## Current Focus
* **PSAA exam April 23, 2026** — PSAP scheduled Q3 2026
* Nebula Forge Detection Suite v2 — 5 tools live (LogNorm, HuntForge, DriftWatch, ClusterIQ, AtomicLoop)
* Purple team automation pipelines: drift-scan and purple-loop
* Expanding Wazuh SIEM detections and Splunk correlation rules



## Certifications

**In Progress:**
- 🔹 PSAA (Practical Junior Security Awareness Analyst) - 2026*
- 🔹 PSAP (Practical SOC Analyst Professional) - *Scheduled Q4 2026*

**Certification Roadmap:**

PSAA → PSAP → Sec+ → CCDL1 → PAPA → PJPT + PNPT

## Lab Environments
**22+ VM Purple Team Lab:**
* Active Directory lab (attack & defense)
* Snort IDS/IPS network monitoring
* Web vulnerability testing environment
* Malware analysis sandbox
* WiFi penetration testing lab
* Flipper Zero / Pwnagotchi
* Wazuh SIEM with Sysmon integration & MITRE ATT&CK-mapped detections (5 agents across Windows/Linux/Kali)
* Splunk Free on Ubuntu for detection and hunt workflows



## Operating Systems

[![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)](https://www.kali.org/)  [![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/software-download) [![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/) [![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)](https://www.debian.org/)


## Security Tools

**Offensive:**
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat-000000?style=for-the-badge)
![BloodHound](https://img.shields.io/badge/BloodHound-DD0031?style=for-the-badge)
![CrackMapExec](https://img.shields.io/badge/CrackMapExec-1A1A1A?style=for-the-badge)

**Defensive:**
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
[![Wazuh](https://img.shields.io/badge/Wazuh-3C82F8?style=for-the-badge&logo=wazuh&logoColor=white)](https://wazuh.com/)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk)
![Elastic](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-F5001D?style=for-the-badge)
![YARA](https://img.shields.io/badge/YARA-009688?style=for-the-badge)
![Sysmon](https://img.shields.io/badge/Sysmon-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)


**Hardware:**
![Flipper Zero](https://img.shields.io/badge/Flipper_Zero-FF6633?style=for-the-badge)
![Pwnagotchi](https://img.shields.io/badge/Pwnagotchi-000000?style=for-the-badge)






##




![Syntax Eyes](syntax-eyes.gif)


**Breaking to Build. Defending to Endure.**

![image_alt](https://github.com/Rootless-Ghost/Epyon-Nebula/blob/main/Peronist%20gundam.gif)








###
