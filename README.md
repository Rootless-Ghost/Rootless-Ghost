<div align="center">

![Title](svgfiles/header-title.svg)

---
 
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=1000&color=9D1AF7&center=true&multiline=true&width=600&lines=Trained+for+chaos.+Built+for+defense.;Rootless.+Relentless.+Ready.;From+combat+zones+to+kill+chains.)](https://git.io/typing-svg)
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=1000&color=00D4FF&center=true&multiline=true&width=600&lines=I+break+it+to+understand+it.;I+defend+it+because+I+can.;The+work+speaks+when+I+don't.)](https://git.io/typing-svg)

![Tagline](svgfiles/header-tagline.svg)

 </div>

 ---
<br>

![Chillin](chillin-S13-c.gif)

<br>

![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%201%25-red?style=for-the-badge&logo=tryhackme)

[![TryHackMe Badge](https://tryhackme-badges.s3.amazonaws.com/RG.Nebula.png?v=10)](https://tryhackme.com/p/RG.Nebula)

[![Obsidian](https://img.shields.io/badge/Obsidian-483699?style=for-the-badge&logo=obsidian&logoColor=white)](https://obsidian.md/) [![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion) [![TCM Security](https://img.shields.io/badge/TCM_Security-Student-9D1AF7?style=for-the-badge)](https://tcm-sec.com/)

<br>

$\color{Goldenrod}\Large{\textsf{About Me}}$
---
<br>

**Former Navy Corpsman** to cybersecurity with real-world combat experience. I bring military discipline, high-pressure decision-making skills, and a systematic approach to threat detection and incident response.

Purple Team & SOC Focus — building both offensive and defensive capabilities                                                                                                                                
Operating a 22+ VM home lab for attack simulation and detection engineering  
Pursuing **PSAA → PSAP → Security+ → CCDL1 → PAPA → PJPT → PNPT** certification path  
**(Inactive) TryHackMe Top 1%** - 270+ rooms completed         
Actively seeking **SOC Analyst & Purple Team** roles

<br>

$\color{Goldenrod}\Large{\textsf{What I Do}}$
---
<br>

$\color{Red}\normalsize{\textsf{Red Team}}$
- Penetration Testing & Security Research
- Red team operations & exploitation
- Active Directory & Windows exploitation
- Network security & privilege escalation

$\color{LightSkyBlue}\normalsize{\textsf{Blue Team}}$
- Threat detection & incident response
- SIEM analysis & log correlation
- Threat hunting & malware analysis
- Security monitoring & alerting

<br>

$\color{Goldenrod}\Large{\textsf{Featured Projects}}$
---
<br>

$\color{MediumOrchid}\large{\textsf{Nebula Forge Detection Suite v2}}$

All 20 tools are part of **[Nebula Forge](https://github.com/Rootless-Ghost/nebula-forge)** — an open-source SOC platform covering the full workflow: Detect → Normalize → Hunt → Drift → Cluster → Simulate → Investigate → Respond → Report. The Detection Suite v2 runs as a fully containerized stack — 7 tools, a shared Postgres backend, and a central dashboard — a single `docker compose up -d` starts all services with a shared Postgres backend. The dashboard (port 5010) provides live status, one-click launches, and pipeline monitoring across all 20 tools in the org.

Nebula Forge includes two automated pipelines:
- **Drift-scan** — scheduled Sigma rule drift analysis across your detection library
- **Purple-loop** — end-to-end purple team cycle: discover (VulnForge) → simulate (AtomicLoop) → detect (Wazuh/Splunk) → validate (DriftWatch) → hunt (HuntForge) | *Pipeline validated end-to-end April 2026*

<br>

 $\color{green}\normalsize{\textsf{Detection Engineering}}$
 ---
 | Tool | Description |
|------|-------------|
| [SigmaForge](https://github.com/Rootless-Ghost/SigmaForge) | Vendor-agnostic Sigma rule generator — Splunk SPL, Elastic KQL/EQL, Sentinel KQL, Wazuh XML, QRadar AQL, Detection-as-Code JSON |
| [YaraForge](https://github.com/Rootless-Ghost/YaraForge) | YARA rule generator with ATT&CK mapping and detection dashboard |
| [SnortForge](https://github.com/Rootless-Ghost/SnortForge) | Snort 2/3 rule generator with multi-content chaining, performance scoring, and 12 detection templates |
| [Azure-SOC-mini-lab](https://github.com/Rootless-Ghost/azure-soc-mini-lab) | Azure cloud detection lab — 12 ATT&CK-mapped simulations, KQL detections, Sentinel playbooks |
| [AWS-SOC-lab](https://github.com/Rootless-Ghost/aws-soc-lab) | AWS cloud detection lab — CloudTrail detections, IAM/S3/EC2 attack simulations, GuardDuty integration |

**[YaraForge](https://github.com/Rootless-Ghost/YaraForge)** - YARA Rule Generator & Testing Platform  
Build, manage, test, and visualize YARA detection rules with MITRE ATT&CK mapping and a detection dashboard.  
`Python` `Flask` `YARA` `MITRE ATT&CK` `Detection Engineering`

**[SnortForge](https://github.com/Rootless-Ghost/SnortForge)** - SnortForge - Snort IDS/IPS Rule Generator — Flask web app with multi-content chaining, Snort 2/3 syntax toggle, rule performance scoring, 12 detection templates, inline help tooltips, PCRE flag checkboxes, HTTP URI/Header matching, rule validation, and .rules file import/export. Dark-themed UI with real-time live preview. v1.2.0.
`Python` `Flask` `Snort` `IDS/IPS` `Network Security`

**[SigmaForge](https://github.com/Rootless-Ghost/SigmaForge)** — Vendor-Agnostic Sigma Rule Generator
Custom conversion engine (no pySigma dependency) generating Sigma rules 
to 6 SIEM backends: Splunk SPL, Elastic KQL, EQL, Sentinel KQL, Wazuh XML, 
and QRadar AQL — plus Detection-as-Code JSON. MITRE ATT&CK mapping, 
12 pre-built templates, rule library, and standalone CLI.
Python Flask Sigma SIEM Detection Engineering CLI
`Python` `Flask` `Sigma` `SIEM` `Detection Engineering` `CLI`

**[Azure-SOC-mini-lab](https://github.com/Rootless-Ghost/Azure-SOC-Mini-Lab)** — Azure Cloud Detection Lab
KQL detections, attack simulations (12 MITRE ATT&CK techniques mapped), and IR documentation for the Azure control plane — identity, compute, and key vault planes. Built on Microsoft Sentinel / Log Analytics with anomaly-based detection, synthetic log samples, and an automated NSG response playbook.
`Azure` `KQL` `Microsoft Sentinel` `MITRE ATT&CK` `Detection Engineering` `Cloud Security`

**[AWS-SOC-lab](https://github.com/Rootless-Ghost/AWS-SOC-Lab)** — AWS Cloud Detection Lab
CloudTrail-based detections in CloudWatch Logs Insights and Athena SQL, attack simulations for IAM privilege escalation, credential exfiltration, S3 enumeration and public exposure, CloudTrail disable, and EC2 post-exploitation via SSM RunCommand — with GuardDuty finding integration, 5 IR reports, and a Lambda auto-response playbook. AWS companion to Azure-SOC-mini-lab.
`AWS` `CloudTrail` `GuardDuty` `CloudWatch Logs Insights` `Athena` `MITRE ATT&CK` `Detection Engineering` `Cloud Security`

$\color{MediumOrchid}\normalsize{\textsf{Nebula Forge Detection Suite v2}}$
---
| Tool | Port | Description |
|------|------|-------------|
| [LogNorm](https://github.com/Rootless-Ghost/LogNorm) | 5006 | ECS-lite log normalizer for disparate SIEM sources |
| [HuntForge](https://github.com/Rootless-Ghost/HuntForge) | 5007 | ATT&CK-mapped threat hunt playbook generator |
| [DriftWatch](https://github.com/Rootless-Ghost/DriftWatch) | 5008 | Sigma rule drift analyzer — feeds the drift-scan pipeline |
| [ClusterIQ](https://github.com/Rootless-Ghost/ClusterIQ) | 5009 | Behavioral alert clustering engine for SOC triage noise reduction |
| [AtomicLoop](https://github.com/Rootless-Ghost/AtomicLoop) | 5011 | Atomic Red Team runner — feeds the purple-loop pipeline |
| [VulnForge](https://github.com/Rootless-Ghost/VulnForge) | 5012 | Exploit intel aggregator → ATT&CK mapping → pipeline trigger |
| [WifiForge](https://github.com/Rootless-Ghost/WifiForge) | 5013 | 802.11 threat detector with deauth/rogue AP detection → LogNorm export |
| [AgentWatch](https://github.com/Rootless-Ghost/AgentWatch) | **—** | **Wazuh agent health monitor — real-time disconnection detection, state change alerting, and JSON log events for SIEM ingestion** |
 
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
 
**[VulnForge](https://github.com/Rootless-Ghost/VulnForge)** - Vulnerability & Exploit Intelligence Tool *(port 5012)*  
Aggregates exploit intelligence from ExploitDB, NVD, and Metasploit, maps findings to MITRE ATT&CK techniques, and feeds results into the purple team pipeline — generating hunt playbooks, LogNorm-ready exports, and AtomicLoop simulation triggers from a single search.  
`Python` `Flask` `MITRE ATT&CK` `Vulnerability Intelligence` `Purple Team`
 
**[WifiForge](https://github.com/Rootless-Ghost/WifiForge)** - Wireless Network Security Analyzer *(port 5013)*  
Passively scans wireless networks, assesses security posture, detects deauth attacks and rogue configurations, maps findings to MITRE ATT&CK techniques, and exports results to the Nebula Forge LogNorm pipeline.  
`Python` `Flask` `Scapy` `Wireless Security` `MITRE ATT&CK`

**[AgentWatch](https://github.com/Rootless-Ghost/AgentWatch)** — Wazuh Agent Health Monitor**
Lightweight Rust binary that polls the Wazuh REST API, surfaces disconnected and never-connected agents in real time, detects state transitions, and emits structured JSON log events compatible with Wazuh log ingestion. Runs as a persistent monitor alongside the Nebula Forge stack.
`Rust` `Wazuh` `Lab Infra` `SOC` `SIEM` `Agent Monitoring`

$\color{green}\normalsize{\textsf{Endpoint Security}}$
---
| Tool | Description |
|------|-------------|
| [EndpointForge](https://github.com/Rootless-Ghost/EndpointForge) | Cross-platform HIDS — process, FIM, network, registry, autoruns with Wazuh NDJSON export |
| [EndpointTriage](https://github.com/Rootless-Ghost/EndpointTriage) | PowerShell IR artifact collector — processes, persistence, event logs, Sysmon, HTML report output |

**[EndpointForge](https://github.com/Rootless-Ghost/EndpointForge)** - Cross-Platform Endpoint Security Monitor  
Host-based intrusion detection and endpoint triage across 5 modules: process execution, file integrity (SHA-256 FIM), network connections, registry persistence (Windows), and autoruns — all MITRE ATT&CK mapped. Includes **Wazuh export integration**: `POST /api/wazuh/export` writes NDJSON picked up by the Wazuh agent using bundled decoder and rules (IDs 100200–100265) with ATT&CK technique tags — no manual log shipping. Markdown/JSON report generation for IR workflows.  
`Python` `Flask` `MITRE ATT&CK` `HIDS` `Endpoint Security` `Wazuh`
 
**[EndpointTriage](https://github.com/Rootless-Ghost/EndpointTriage)** - Windows Endpoint Forensic Artifact Collector  
Automated PowerShell-based IR triage script that collects volatile and non-volatile forensic artifacts — running processes with hashes, network connections, registry persistence checks, scheduled tasks, event log extraction (Security, Sysmon, PowerShell, Defender), named pipe enumeration, and suspicious indicator flagging. Outputs a structured triage package with HTML summary report.  
`PowerShell` `Incident Response` `Forensics` `DFIR` `Endpoint Security`

$\color{green}\normalsize{\textsf{Blue Team}}$
---
| Tool | Description |
|------|-------------|
| [Log-Analyzer](https://github.com/Rootless-Ghost/Log-Analyzer) | SOC-focused log analysis with pattern matching and anomaly detection |
| [Phishing-Analyzer](https://github.com/Rootless-Ghost/Phishing-Analyzer) | Email header and content analysis for phishing campaign identification |

**[Log-Analyzer](https://github.com/Rootless-Ghost/log-Analyzer)** - Security Log Analyzer  
Python-based log analysis tool designed for SOC analysts with pattern matching and anomaly detection.  
`Python` `Flask` `SIEM` `Log Analysis` `SOC`

**[Phishing-Analyzer](https://github.com/Rootless-Ghost/Phishing-Analyzer)** - Phishing Email Analyzer  
Email header and content analysis tool for identifying phishing campaigns and malicious indicators.  
`Python` `Email Security` `Phishing Detection` `Blue Team`

$\color{green}\normalsize{\textsf{Threat Intelligence}}$
---
| Tool | Description |
| --- | --- |
| [Threat-Intel-Dashboard](https://github.com/Rootless-Ghost/Threat-Intel-Dashboard) | Real-time IOC tracking, feed aggregation, and visual analytics for SOC operations |
| [ThreatTape](https://github.com/Rootless-Ghost/ThreatTape) | Live IOC threat intel feed — AbuseIPDB + OTX aggregation with MITRE ATT&CK tagging |

**[Threat-Intel-Dashboard](https://github.com/Rootless-Ghost/Threat-Intel-Dashboard)** - Threat Intelligence Dashboard  
Real-time threat intelligence platform with IOC tracking, feed aggregation, and visual analytics for SOC operations.  
`HTML` `JavaScript` `Threat Intelligence` `OSINT` `SOC`

**[ThreatTape](https://github.com/Rootless-Ghost/ThreatTape)** - Live IOC Threat Intel Feed *(port 5014)*  
Aggregates indicators of compromise from AbuseIPDB and AlienVault OTX, displays live IOC data with severity scoring, country of origin, community report counts, and MITRE ATT&CK technique tags. Falls back to curated mock data with no API keys required.  
`Python` `Flask` `Threat Intelligence` `IOC` `MITRE ATT&CK` `AbuseIPDB` `OTX`

$\color{green}\normalsize{\textsf{Incident Response}}$
---
| Tool | Description |
|------|-------------|
| [SIREN](https://github.com/Rootless-Ghost/SIREN) | NIST 800-61 incident report generator with severity scoring, IOC tracking, and timeline management |

**[SIREN](https://github.com/Rootless-Ghost/SIREN)** - Security Incident Response Engine & Notation  
Professional incident report generator following NIST 800-61 framework with severity scoring, IOC tracking, timeline management, and Markdown/JSON export.  
`Python` `Flask` `NIST 800-61` `Incident Response` `SOC`


$\color{green}\normalsize{\textsf{Training}}$
---
| Tool | Description |
| --- | --- |
| [WarGameForge](https://github.com/Rootless-Ghost/WarGameForge) | SOC investigation scenario generator — MITRE-driven, difficulty-scaled training |
| [Security-Awareness-Training](https://github.com/Rootless-Ghost/Security-Awareness-Training) | Enterprise-style phishing simulation and security awareness training platform |

**[WarGameForge](https://github.com/Rootless-Ghost/WarGameForge)** - SOC Investigation Scenario Generator
Generates realistic SOC investigation scenarios from MITRE ATT&CK techniques — complete with SIEM alert blocks, investigation clues, red herring artifacts, and step-by-step solution walkthroughs. Difficulty-scaled from easy to hard, 12 built-in techniques plus custom input.
`Python` `Flask` `SOC Training` `MITRE ATT&CK` `Detection Engineering` `Blue Team`

**[Security-Awareness-Training](https://github.com/Rootless-Ghost/Security-Awareness-Training)** - Security Awareness Platform
Enterprise-style platform with phishing simulations, training modules, and progress tracking.
`Python` `Flask` `Security Training` `Phishing Simulation`



$\color{green}\normalsize{\textsf{Wireless Security}}$
---
| Tool | Description |
|------|-------------|
| [Hidden-Rogue-AP-Detector](https://github.com/Rootless-Ghost/Hidden-Rogue-AP-Detector) | Rogue AP detection via RSSI analysis with whitelist management |
| [Wi-Fi-Probe-Request-Sniffer](https://github.com/Rootless-Ghost/Wi-Fi-Probe-Request-Sniffer) | 802.11 probe request capture with MAC vendor ID and CSV/JSON export |

**[Hidden-Rogue-AP-Detector](https://github.com/Rootless-Ghost/Hidden-Rogue-AP-Detector)** - Rogue Access Point Detector
Python-based wireless security tool for detecting unauthorized access points using RSSI signal strength analysis, whitelist management, and active/passive scanning modes.
`Python` `Scapy` `Wireless Security` `Network Monitoring` `Rogue AP Detection`

**[Wi-Fi-Probe-Request-Sniffer](https://github.com/Rootless-Ghost/Wi-Fi-Probe-Request-Sniffer)** - Wi-Fi Probe Request Analyzer
Captures and analyzes wireless probe requests from nearby devices with SSID extraction, MAC vendor identification, and CSV/JSON export for network visibility and device enumeration.
`Python` `Scapy` `802.11` `Network Security` `Device Enumeration`

$\color{green}\normalsize{\textsf{Offensive Security Tools}}$
---
| Tool | Description |
|------|-------------|
| [SMB-RDP-Exploitation-Scanner](https://github.com/Rootless-Ghost/SMB-RDP-Exploitation-Scanner) | SMB/RDP vulnerability scanner — EternalBlue, SMBGhost, BlueKeep, credential brute force |
| [Network-Security-Toolkit](https://github.com/Rootless-Ghost/network-security-toolkit) | PathFinder (attack path mapping) + PathGuard (defensive hardening) on shared NetworkMapper core |

**[SMB-RDP-Exploitation-Scanner](https://github.com/Rootless-Ghost/SMB-RDP-Exploitation-Scanner)**  — SMB & RDP Vulnerability Scanner
Python-based exploitation scanner for authorized penetration testing. Detects and validates SMB vulnerabilities (EternalBlue MS17-010, SMBGhost CVE-2020-0796, null session enumeration) and RDP vulnerabilities (BlueKeep CVE-2019-0708) with credential brute forcing, multi-format reporting (JSON/CSV/TXT), and threaded subnet scanning. Designed for Kali Linux.
`Python` `Penetration Testing` `SMB` `RDP` `Network Security` `Vulnerability Assessment`

**[Network-Security-Toolkit](https://github.com/Rootless-Ghost/Network-Security-Toolkit)** — PathFinder & PathGuard
Unified red/blue team network security toolkit built on a shared core library (NetworkMapper). PathFinder maps attack paths, lateral movement routes, and exfiltration channels with Shodan integration and MITRE ATT&CK coverage. PathGuard provides defensive choke point analysis, CIS/NIST-mapped hardening recommendations, baseline change detection, and a prioritized remediation roadmap.
`Python` `Red Team` `Blue Team` `Network Security` `MITRE ATT&CK` `Shodan` `PathFinder` `PathGuard`

<br>

$\color{Goldenrod}\Large{\textsf{Current Focus}}$
---
<br>

- Nebula Forge Detection Suite v2 — 7 tools containerized and live (LogNorm, HuntForge, DriftWatch, ClusterIQ, AtomicLoop, VulnForge, WifiForge) + dashboard (5010) + Postgres — single `docker compose up -d`
- Purple team automation pipelines: drift-scan and purple-loop validated end-to-end April 2026
- PSAP 2026 — SOC analyst and detection engineering roles
- Expanding Wazuh SIEM detections and Splunk correlation rules

<br>

$\color{Goldenrod}\Large{\textsf{Certifications}}$
---

<br>

**In Progress:**
- 🔹 PSAA (Practical SOC Analyst Associate) - 2026*
- 🔹 PSAP (Practical SOC Analyst Professional) - *Scheduled Q4 2026*
  
<br>

**Certification Roadmap:**
PSAA → PSAP → Sec+ → CCDL1 → PAPA → PJPT + PNPT

<br>

$\color{Goldenrod}\Large{\textsf{Lab Environments}}$
---
<br>

**22+ VM Purple Team Lab:**
* Active Directory lab (attack & defense)
* Snort IDS/IPS network monitoring
* Web vulnerability testing environment
* Malware analysis sandbox
* WiFi penetration testing lab
* Flipper Zero / Pwnagotchi
* Wazuh SIEM with Sysmon integration & MITRE ATT&CK-mapped detections (5 agents: Windows, Linux)
* Splunk Free on Ubuntu for detection and hunt workflows

<br>

$\color{Goldenrod}\Large{\textsf{Operating Systems}}$
---
<br>

[![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)](https://www.kali.org/)  [![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/software-download) [![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/) [![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)](https://www.debian.org/)

<br>

$\color{Goldenrod}\Large{\textsf{Security Tools}}$
---
<br>

$\color{red}\normalsize{\textsf{Offensive }}$
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat-000000?style=for-the-badge)
![BloodHound](https://img.shields.io/badge/BloodHound-DD0031?style=for-the-badge)
![CrackMapExec](https://img.shields.io/badge/CrackMapExec-1A1A1A?style=for-the-badge)

$\color{CornflowerBlue}\normalsize{\textsf{Defensive }}$
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
[![Wazuh](https://img.shields.io/badge/Wazuh-3C82F8?style=for-the-badge&logo=wazuh&logoColor=white)](https://wazuh.com/)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk)
![Elastic](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-F5001D?style=for-the-badge)
![YARA](https://img.shields.io/badge/YARA-009688?style=for-the-badge)
![Sysmon](https://img.shields.io/badge/Sysmon-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)


$\color{CornflowerBlue}\normalsize{\textsf{Hardware }}$
![Flipper Zero](https://img.shields.io/badge/Flipper_Zero-FF6633?style=for-the-badge)
![Pwnagotchi](https://img.shields.io/badge/Pwnagotchi-000000?style=for-the-badge)




<br><br>



![Syntax Eyes](syntax-eyes.gif)


**Breaking to Build. Defending to Endure.**

![image_alt](https://github.com/Rootless-Ghost/Epyon-Nebula/blob/main/Peronist%20gundam.gif)








###
