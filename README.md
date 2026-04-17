<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00BFFF&center=true&vCenter=true&width=600&lines=Alejandro+Zavala;Cybersecurity+Professional;ISC2+CC+Certified;SOC+Operations+Analyst;Defending+perimeters+one+log+at+a+time...)](https://git.io/typing-svg)

</div>

---

```
┌──(alejandro㉿sec-ops)-[~]
└─$ whoami --verbose
```

```
> Name   : Alejandro Zavala Zenteno
> Role   : Jr. Cybersecurity Professional & (soon to be) Computational Systems Engineer
> Cert   : ISC2 Certified in Cybersecurity (CC) · 2026–2029
> Base   : Morelia, Michoacán · Mexico  [UTC-6]
> Focus  : SOC Operations | Detection Engineering | SIEM/XDR | Incident Response
> Status : [ Seeking remote security roles · Open to opportunities ]
```

---

```
┌──(alejandro㉿sec-ops)-[~]
└─$ cat featured_project.md
```

<table>
<tr>
<td>

### [wazuh-soc-homelab](https://github.com/alejandroZ345/wazuh-soc-homelab)

Enterprise-grade **Wazuh SIEM/XDR + TheHive IRP** deployment — 9 phases covering the full SOC pipeline from stack deployment to automated incident response.

**Highlights:**
- 5 custom XML detection rules (behavioral TTPs)
- MITRE ATT&CK mapping across 7 techniques
- Automated containment (<2s detection-to-block)
- TheHive v5 integration via custom Python API bridge
- 5 standardized triage runbooks

`wazuh` `docker` `mitre-attack` `detection-engineering` `thehive` `active-response`

</td>
</tr>
</table>

---

```
┌──(alejandro㉿sec-ops)-[~]
└─$ cat currently_running.log
```

```
[*] Wazuh SIEM Home Lab ........................ COMPLETE (9/9 phases)
    └─ Custom XML rules deployed ............... 5 rules (100001–100005)
    └─ Detection strategy ...................... Behavioral TTPs (Pyramid of Pain)
    └─ ATT&CK techniques covered ............... T1110 · T1078 · T1548 · T1565 · T1087 · T1082 · T1095
    └─ Active response mechanisms .............. firewall-drop (IP ban) + custom alert script
    └─ IRP integration ......................... TheHive v5 ← Wazuh (custom Python API bridge)
    └─ Triage runbooks published ............... 5 (one per custom rule)
    └─ Agents reporting ........................ Windows + Linux
    └─ SOC dashboard ........................... Custom OpenSearch KPI panel (5 visualizations)

[*] Next objectives ............................ QUEUED
    └─ [ ] ???
```

---

```
┌──(alejandro㉿sec-ops)-[~]
└─$ cat skill_matrix.txt
```

```
[ Security Operations ]
  SIEM/XDR      ██████████░  Wazuh · OpenSearch · Custom dashboards · Active response
  Detection Eng ████████░░░  XML rules · Behavioral TTPs · Telemetry analysis · Rule tuning
  Threat Hunt   ████████░░░  FIM · Auth correlation · Discovery · C2 detection
  Incident Resp ████████░░░  TheHive v5 · Triage runbooks · Containment SOPs · Kill chain analysis
  Frameworks    ███████░░░░  MITRE ATT&CK · NIST CSF · ISO/IEC 27001 (via ISC2 CC)

[ Infrastructure ]
  Linux         █████████░░  Ubuntu hardening · Debian · Bash scripting · syslog pipelines
  Containers    ████████░░░  Docker · Docker Compose · WSL2 · IaC credential management
  Windows       ██████░░░░░  PowerShell · WazuhSvc · AD basics

[ Networking ]
  Protocols     ███████░░░░  TCP/IP · DNS · SSH · VPN (Sophos)
  Hardware      ██████░░░░░  Cisco · Ruckus · Switches · Routers
  Analysis      ██████░░░░░  Wireshark · Nmap · Firewall config · iptables

[ Offensive (lab only) ]
  Tools         ██████░░░░░  Hydra · Nmap · Nikto · Metasploit · Kali · Reverse shells
```

---

```
┌──(alejandro㉿sec-ops)-[~]
└─$ ls -la projects/
```

```
drwxr-xr-x  wazuh-soc-homelab/
│
├── Phase 1 · Stack deployment & credential hardening     [✓ DONE]
├── Phase 2 · Windows agent & lifecycle management        [✓ DONE]
├── Phase 3 · Linux agent & SSH brute-force simulation    [✓ DONE]
│            └─ 1,815 auth failures · Level 10 alert triggered
├── Phase 4 · File Integrity Monitoring (FIM)             [✓ DONE]
│            └─ /etc/passwd tampering · Rules 554 & 550
├── Phase 5 · Custom detection engineering & rule tuning  [✓ DONE]
│            └─ Rules 100001–100005 · Pyramid of Pain shift
│            └─ bash_audit pipeline · Behavioral TTP detection
├── Phase 6 · MITRE ATT&CK mapping & standardization     [✓ DONE]
│            └─ 7 techniques mapped · 5 triage runbooks
├── Phase 7 · Custom SOC dashboard engineering            [✓ DONE]
│            └─ 5 KPI visualizations · OpenSearch bypass
├── Phase 8 · Active response & automated containment     [✓ DONE]
│            └─ firewall-drop IP ban · <2s detection-to-block
│            └─ 3 WSL2 architectural discoveries resolved
└── Phase 9 · TheHive IRP integration & API automation    [✓ DONE]
             └─ Custom Python API bridge · RBAC config
             └─ I/O race condition resolved · 100% alert delivery
```

---

```
┌──(alejandro㉿sec-ops)-[~]
└─$ cat /etc/motd
```

```
"The goal is not to be better than everyone else,
 but to be better than you were yesterday."

Building in public · Documenting every step · Failing forward.
```

---

<div align="center">

**[ Stack ]**

![Wazuh](https://img.shields.io/badge/Wazuh-4.14.4-00a2e8?style=flat-square)
![TheHive](https://img.shields.io/badge/TheHive-5.2.11-FFCC00?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-29.3.1-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-WSL2-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-Offensive-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-Dashboards-005EB8?style=flat-square)
![Python](https://img.shields.io/badge/Python-Scripting-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Automation-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-Mapped-FF0000?style=flat-square)

**[ Connect ]**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alejandro_Zavala-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-zavala-zenteno)
[![ISC2](https://img.shields.io/badge/ISC2-CC_Certified-green?style=flat-square)](https://www.credly.com/badges/fe6eeefe-d684-45fa-8f57-9f7d025db2d6/public_url)
[![TryHackMe](https://tryhackme-badges.s3.amazonaws.com/alejandro.zavala.zenteno.png)](https://tryhackme.com/p/alejandro.zavala.zenteno)

</div>

---

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=400&size=14&pause=1000&color=00BFFF&center=true&vCenter=true&width=450&lines=%24+echo+%22Thanks+for+stopping+by.%22;%24+echo+%22Feel+free+to+explore+the+lab.%22;%24+exit+0)](https://git.io/typing-svg)

</div>
