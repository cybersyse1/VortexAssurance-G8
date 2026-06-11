<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=220&section=header&text=VortexAssurance&fontSize=48&fontAlignY=38&desc=Audit%20Technique%2C%20Red%20Team%20%26%20Gouvernance&descAlignY=58&descAlign=50&fontColor=00d4ff" />
</div>

<div align="center">
<img src="https://img.shields.io/badge/Role-Project_Manager_%26_Compliance_Lead-E34F26?style=for-the-badge&logo=shield&logoColor=white" />
<img src="https://img.shields.io/badge/Project-VortexOps_Inc.-0052CC?style=for-the-badge&logo=server&logoColor=white" />
<img src="https://img.shields.io/badge/Institution-CCNB_Moncton-FCC624?style=for-the-badge&logo=graduation-cap&logoColor=black" />
<img src="https://img.shields.io/badge/Result-3rd_Place_Bronze-CD7F32?style=for-the-badge&logo=trophy&logoColor=white" />
</div>

---

## About This Project

**VortexAssurance (Group 8)** is a comprehensive cybersecurity audit, Red Team assessment, and governance project conducted as part of the **VortexOps Inc.** initiative at the Collège Communautaire du Nouveau-Brunswick (CCNB), Programme SECS1026.

As an independent control body, Group 8 was mandated to audit, validate, and ensure the security posture of the entire VortexOps ecosystem — covering IAM, CyberRange, core infrastructure, and a CTF platform.

### My Role: Project Manager & Documentation Compliance Lead
- General coordination of all audit and Red Team operations
- Consolidation of the final technical report (Version 6 — FINAL)
- Document governance, arborescence project, and compliance framework
- Ensuring alignment with ISO/IEC 27001 and NIST SP 800-115

---

## Core Security Domains Covered

| Domain | Challenge | Methodology |
|---|---|---|
| Identity & Access Management | AGDLP model, Tiering (Tier0/1/2), Keycloak SSO | Active Directory audit, PowerShell |
| Network Segmentation | VLAN isolation, lateral movement prevention | SSH access, Proxmox console |
| Detection & Incident Response | Wazuh SIEM validation, 80% detection rate | Red Team campaign, 106,153 alerts |
| Resilience & Business Continuity | HA, backups, DRP/PRA evaluation | ha-manager, NFS audit |

---

## Red Team Campaign — MITRE ATT&CK Framework

10 attack scenarios executed from **kali-G8 (10.0.100.12)** against the VortexRange environment:

| # | Tactic | Technique | Tool | Outcome |
|---|---|---|---|---|
| S01 | Reconnaissance | T1595 — Active Scanning | Nmap | Hosts & ports identified |
| S02 | Credential Access | T1110 — Brute Force SSH | Hydra | Credentials cracked |
| S03 | Initial Access | T1190 — SQL Injection | SQLMap | Database extracted |
| S05 | Privilege Escalation | T1548 — sudo NOPASSWD | LinPEAS | Root access obtained |
| S07 | Credential Access | T1003 — NTLM Hash Dump | Secretsdump (Impacket) | Hashes recovered |
| S09 | Exfiltration | T1041 — Data Exfiltration | Netcat / SCP | Data exfiltrated |
| S10 | Persistence | T1505 — Webshell Backdoor | PHP Webshell | Backdoor established |

> **Detection Rate: 80%** — 106,153 total alerts generated in Wazuh (2,769 critical alerts, level ≥ 12)

---

## Audit Methodology — "Gold Standard" Approach

Based on **ISO/IEC 27001** and **NIST SP 800-115**, each audit followed 4 phases:

1. **Preparation** — Document analysis and scope definition
2. **Investigation** — Practical technical verification
3. **Analysis** — Artifact collection and compliance comparison
4. **Reporting** — Risk registry and remediation recommendations

### Audited Groups

| Group | Component | Technologies |
|---|---|---|
| G1 — VortexIAM | Identity & Access Management | Active Directory, GPO, Keycloak SSO |
| G2 — VortexRange | CyberRange Environment | Proxmox VE, OPNsense, Wazuh |
| G6 — VortexCore | Core Infrastructure | Proxmox Cluster (3 nodes), NFS, HA |
| G9 — VortexLabs | CTF Platform | CTFd, Docker Swarm, MariaDB, Redis |

---

## Technologies Used

<p align="center">
<img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" />
<img src="https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=nmap&logoColor=white" />
<img src="https://img.shields.io/badge/Wazuh_SIEM-0052CC?style=for-the-badge&logo=wazuh&logoColor=white" />
<img src="https://img.shields.io/badge/Proxmox_VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Active_Directory-0078D6?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" />
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
</p>

---

## Key Outcomes

- Identified critical architectural flaws: **no VLAN segmentation** in VortexCore (G6), **no HA configured**, exposed NFS storage.
- Generated **106,153 security alerts** including **2,769 critical** during Red Team campaign.
- Delivered a **20-domain compliance matrix** covering all VortexOps groups.
- Produced prioritized remediation plans and acceptance recommendations for all development teams.

> *"This project reinforced my expertise in offensive security, technical auditing, and compliance governance — demonstrating the critical importance of independent security validation in complex IT environments."*

---

<div align="center">
<a href="https://www.linkedin.com/in/mohamed-amine-bengadi-23817a168/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/cybersyse1"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=120&section=footer" />
</div>
