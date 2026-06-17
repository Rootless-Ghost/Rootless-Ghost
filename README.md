<div align="center">

![Title](svgfiles/header-title.svg)

---
 
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=3500&color=9D1AF7&center=true&multiline=true&width=600&lines=Trained+for+chaos.+Built+for+defense.;From+combat+zones+to+kill+chains.)](https://git.io/typing-svg)
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=1000&color=00D4FF&center=true&multiline=true&width=600&height=140&lines=I+break+it+to+understand+it.;I+defend+it+because+I+can.;The+work+speaks+when+I+don't.)](https://git.io/typing-svg)
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

$\color{LightSkyBlue}\normalsize{\textsf{Blue Team}}$
- Threat detection & incident response
- SIEM analysis & log correlation
- Threat hunting & malware analysis
- Security monitoring & alerting

$\color{Red}\normalsize{\textsf{Red Team}}$
- Penetration Testing & Security Research
- Red team operations & exploitation
- Active Directory & Windows exploitation
- Network security & privilege escalation
  
<br>

$\color{Goldenrod}\Large{\textsf{Featured Projects}}$
---
<br>

$\color{MediumOrchid}\large{\textsf{Nebula Forge Detection Suite}}$

**[Nebula Forge](https://github.com/Rootless-Ghost/nebula-forge)** is an open-source SOC platform covering the full workflow: Detect → Normalize → Hunt → Drift → Cluster → Simulate → Investigate → Respond → Report. The full suite runs as a fully containerized stack — 13 containerized tools, 15 services total, a shared Postgres backend, and a central dashboard — clone all repos with the included setup script, then a single `docker compose up -d` starts all services. The dashboard (port 5010) provides live status, one-click launches, and pipeline monitoring across all 18 tools in the org.

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


$\color{MediumOrchid}\large{\textsf{Nebula Forge Detection Suite v1}}$
---
| Tool | Port | Description |
|------|------|-------------|
| [SigmaForge](https://github.com/Rootless-Ghost/SigmaForge) | 5000 | Custom Sigma conversion engine — 6 SIEM backends, Detection-as-Code JSON, no pySigma dependency |
| [YaraForge](https://github.com/Rootless-Ghost/YaraForge) | 5001 | YARA rule builder with live scanning, MITRE ATT&CK tagging, SQLite storage |
| [Threat-Intel-Dashboard](https://github.com/Rootless-Ghost/Threat-Intel-Dashboard) | 5002 | IOC reputation lookup — VirusTotal, AbuseIPDB; auto-type detection; demo mode |
| [SnortForge](https://github.com/Rootless-Ghost/SnortForge) | 5003 | Snort 2/3 rule generator — multi-content chaining, PCRE, 0–100 performance scorer |
| [SIREN](https://github.com/Rootless-Ghost/SIREN) | 5004 | NIST 800-61 IR report builder — timeline, IOC tracking, composite severity scoring |
| [EndpointForge](https://github.com/Rootless-Ghost/EndpointForge) | 5005 | Cross-platform HIDS — process, FIM, network, registry, persistence — Wazuh export |

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
 
$\color{green}\normalsize{\textsf{Endpoint Security}}$
---
| Tool | Description |
|------|-------------|
| [EndpointForge](https://github.com/Rootless-Ghost/EndpointForge) | Cross-platform HIDS — process, FIM, network, registry, autoruns with Wazuh NDJSON export |
| [EndpointTriage](https://github.com/Rootless-Ghost/EndpointTriage) | PowerShell IR artifact collector — processes, persistence, event logs, Sysmon, HTML report output |

$\color{green}\normalsize{\textsf{Blue Team}}$
---
| Tool | Description |
|------|-------------|
| [Log-Analyzer](https://github.com/Rootless-Ghost/Log-Analyzer) | SOC-focused log analysis with pattern matching and anomaly detection |
| [Phishing-Analyzer](https://github.com/Rootless-Ghost/Phishing-Analyzer) | Email header and content analysis for phishing campaign identification |

$\color{green}\normalsize{\textsf{Threat Intelligence}}$
---
| Tool | Description |
| --- | --- |
| [Threat-Intel-Dashboard](https://github.com/Rootless-Ghost/Threat-Intel-Dashboard) | Real-time IOC tracking, feed aggregation, and visual analytics for SOC operations |
| [ThreatTape](https://github.com/Rootless-Ghost/ThreatTape) | Live IOC threat intel feed — AbuseIPDB + OTX aggregation with MITRE ATT&CK tagging |

$\color{green}\normalsize{\textsf{Incident Response}}$
---
| Tool | Description |
|------|-------------|
| [SIREN](https://github.com/Rootless-Ghost/SIREN) | NIST 800-61 incident report generator with severity scoring, IOC tracking, and timeline management |

$\color{green}\normalsize{\textsf{Training}}$
---
| Tool | Description |
| --- | --- |
| [WarGameForge](https://github.com/Rootless-Ghost/WarGameForge) | SOC investigation scenario generator — MITRE-driven, difficulty-scaled training |

$\color{Goldenrod}\large{\textsf{Detection Labs}}$
---
| Lab | Layer | Description |
|-----|-------|-------------|
| [Azure-SOC-mini-lab](https://github.com/Rootless-Ghost/azure-soc-mini-lab) | Azure | KQL detections, 12 ATT&CK-mapped simulations, IR documentation, Sentinel playbooks |
| [AWS-SOC-lab](https://github.com/Rootless-Ghost/aws-soc-lab) | AWS | CloudTrail detections, IAM/S3/EC2 attack sims, GuardDuty integration, Lambda auto-response |
| [Malware-Detonation-Lab](https://github.com/Rootless-Ghost/Malware-Detonation-Lab) | On-Prem | Isolated FLARE-VM + REMnux sandbox, DNS sinkhole, local-capture detection workflow |

<br>

$\color{Goldenrod}\Large{\textsf{Current Focus}}$
---
<br>

- Nebula Forge — 13 tools containerized and live (v1: SigmaForge, YaraForge, Threat-Intel-Dashboard, SnortForge, SIREN, EndpointForge; v2: LogNorm, HuntForge, DriftWatch, ClusterIQ, AtomicLoop, VulnForge, WifiForge) + dashboard (5010) + Postgres, 15 services total — setup scripts + single `docker compose up -d`
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


[![Typing SVG](https://readme-typing-svg.demolab.com?font=Press+Start+2P&weight=200&size=16&pause=1000&color=9D1AF7&center=true&multiline=true&width=600&lines=Breaking+to+Build.;Defending+to+Hold.)](https://git.io/typing-svg)

![image_alt](https://github.com/Rootless-Ghost/Epyon-Nebula/blob/main/Peronist%20gundam.gif)








###
