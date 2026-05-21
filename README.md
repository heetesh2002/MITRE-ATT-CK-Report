# 🛡️ MITRE ATT&CK® Research Report 
## 📋 Assignment Details

| Field | Details |
|---|---|
| **Assigned Campaign** | C0024 — SolarWinds Compromise |
| **Assigned Software Range** | S0240 – S0249 (10 Entries) |
| **Research Platform** | https://attack.mitre.org/ |

---

## 📁 Repository Contents

```
📄 MITRE_ATTandCK_Report_.pdf  — Full research report 
📄 README.md                    — Repository overview
```

---

## 🎯 Part 1: Campaign Research

### C0024 — SolarWinds Compromise

| Attribute | Details |
|---|---|
| **Threat Actor** | APT29 (Cozy Bear / NOBELIUM) |
| **Origin** | Russia — Foreign Intelligence Service (SVR) |
| **Active Period** | August 2019 – January 2021 |
| **Discovered** | December 2020 (FireEye) |
| **Victims** | ~18,000 organizations globally |
| **Primary Targets** | US Government, Technology, Cybersecurity firms |

**Key ATT&CK Techniques:**

| Technique ID | Name |
|---|---|
| T1195.002 | Supply Chain Compromise: Software Supply Chain |
| T1553.002 | Subvert Trust Controls: Code Signing |
| T1606.002 | Forge Web Credentials: SAML Tokens |
| T1078 | Valid Accounts |
| T1568 | Dynamic Resolution (DNS-based C2) |
| T1484.002 | Domain Policy Modification: Trust Modification |

---

## 🛠️ Part 2: Software Research (S0240 – S0249)

| # | ID | Name | Type | Threat Actor |
|---|---|---|---|---|
| 1 | S0240 | ROKRAT | Remote Access Trojan | APT37 (North Korea) |
| 2 | S0241 | RATANKBA | Remote Controller Tool | Lazarus Group (North Korea) |
| 3 | S0242 | SynAck | Targeted Ransomware | Unattributed |
| 4 | S0243 | DealersChoice | Flash Exploitation Framework | APT28 (Russia GRU) |
| 5 | S0244 | Comnie | Remote Access Backdoor | Unattributed (East Asia) |
| 6 | S0245 | BADCALL | Trojan Backdoor | Lazarus Group (North Korea) |
| 7 | S0246 | HARDRAIN | Trojan / Reverse Proxy | Lazarus Group (North Korea) |
| 8 | S0247 | NavRAT | Remote Access Trojan | APT37 (North Korea) |
| 9 | S0248 | yty | Modular RAT Framework | DoNot Team (South Asia) |
| 10 | S0249 | Gold Dragon | Reconnaissance Implant | Lazarus Group (North Korea) |

---

## 📚 Research Areas Covered

Each software entry includes research across all mandatory areas:

- ✅ Name & Type
- ✅ Description & Threat Actor Association
- ✅ Supported Platforms
- ✅ ATT&CK Techniques Used (with Technique IDs)
- ✅ Execution Method
- ✅ Persistence Techniques
- ✅ Privilege Escalation
- ✅ Defense Evasion
- ✅ Credential Access
- ✅ Discovery Techniques
- ✅ Lateral Movement
- ✅ Command & Control (C2)
- ✅ Exfiltration
- ✅ Impact Analysis
- ✅ Indicators of Compromise (IOCs)
- ✅ Detection & Mitigation
- ✅ References & Sources

---

## 🔗 References & Sources

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [MITRE ATT&CK Campaign C0024](https://attack.mitre.org/campaigns/C0024/)
- [S0240 — ROKRAT](https://attack.mitre.org/software/S0240/)
- [S0241 — RATANKBA](https://attack.mitre.org/software/S0241/)
- [S0242 — SynAck](https://attack.mitre.org/software/S0242/)
- [S0243 — DealersChoice](https://attack.mitre.org/software/S0243/)
- [S0244 — Comnie](https://attack.mitre.org/software/S0244/)
- [S0245 — BADCALL](https://attack.mitre.org/software/S0245/)
- [S0246 — HARDRAIN](https://attack.mitre.org/software/S0246/)
- [S0247 — NavRAT](https://attack.mitre.org/software/S0247/)
- [S0248 — yty](https://attack.mitre.org/software/S0248/)
- [S0249 — Gold Dragon](https://attack.mitre.org/software/S0249/)
- [Cisco Talos — ROKRAT Analysis](https://blog.talosintelligence.com/2017/04/introducing-rokrat.html)
- [Trend Micro — RATANKBA](https://www.trendmicro.com/en_us/research/17/b/ratankba-watering-holes-against-enterprises.html)
- [Kaspersky — SynAck Doppelganging](https://securelist.com/synack-targeted-ransomware-uses-the-doppelganging-technique/85431/)
- [Palo Alto Unit 42 — DealersChoice](https://researchcenter.paloaltonetworks.com/2016/10/unit42-dealerschoice-sofacys-flash-player-exploit-platform/)
- [Palo Alto Unit 42 — Comnie](https://unit42.paloaltonetworks.com/unit42-comnie-continues-target-organizations-east-asia/)
- [CISA — Hidden Cobra Advisory](https://www.cisa.gov/news-events/alerts/2017/11/14/hidden-cobra-north-koreans-ddos-botnet-infrastructure)
- [Cisco Talos — NavRAT](https://blog.talosintelligence.com/2018/05/navrat.html)
- [Trend Micro — Gold Dragon / PyeongChang](https://blog.trendmicro.com/trendlabs-security-intelligence/lazarus-campaign-pyeongchang-winter-olympics/)

---

## ⚠️ Disclaimer

This report is submitted solely for the MITRE ATT&CK Research. All research is based on publicly available threat intelligence and official MITRE ATT&CK documentation. No malicious tools or techniques were developed or deployed.

---

*MITRE ATT&CK | May 2026*
