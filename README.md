# Working-with-Threat-Feeds

# 🛡️ Working with Threat Feeds & Exploit Database
### CompTIA Security+ Assisted Lab | Threat Intelligence & Vulnerability Management

## 📌 Overview

This lab explores how cybersecurity professionals use **threat intelligence feeds**, **Indicators of Compromise (IoCs)**, and the **Exploit Database** to strengthen an organization's security posture.

Throughout this lab, you will examine real-world threat intelligence resources, learn how IoCs assist with threat hunting and incident response, and explore the Exploit Database for vulnerability research and exploit information.

---

## 🎯 Objectives

This lab aligns with the following **CompTIA Security+ (SY0-701)** objective:

- **4.3 – Explain various activities associated with vulnerability management**

By completing this lab, you will learn how to:

- Understand Indicators of Compromise (IoCs)
- Explore open-source threat intelligence feeds
- Analyze AlienVault OTX threat intelligence
- Research vulnerabilities using Exploit Database
- Understand Google Hacking Database (GHDB)
- Identify valuable vulnerability management resources

---

# 🖥️ Lab Environment

| Component | Details |
|-----------|----------|
| Platform | Local Web Browser |
| Organization | Structureality Inc. |
| Internet Access | Required (performed outside the lab VM) |

---

# Part 1 — Understanding Threat Intelligence Sources

Threat intelligence feeds provide continuously updated information about:

- Malicious IP addresses
- Malware hashes
- Malicious domains
- URLs
- Botnets
- Threat actors
- Indicators of Compromise (IoCs)

Security Operations Centers (SOCs) use these feeds to:

- Detect attacks
- Improve SIEM detection rules
- Hunt threats
- Block malicious infrastructure
- Investigate incidents faster

---

# Exploring CIS Threat Feeds

Visited:

> CIS Real-Time Indicator Feeds

The CIS (Center for Internet Security) provides cyber threat intelligence primarily for:

- State governments
- Local governments
- Tribal governments
- Territorial governments (SLTT)

These feeds help organizations proactively defend against cyber threats.

---

# Exploring AlienVault OTX

The lab explores **AlienVault Open Threat Exchange (OTX)**.

OTX provides community-shared threat intelligence called:

> **Pulses**

A Pulse contains collections of:

- IoCs
- Malware indicators
- IP addresses
- URLs
- Domains
- File hashes
- Threat reports

---

## Mirai Botnet Investigation

Search performed:

```
mirai
```

Example Pulse:

```
Mirai Botnet IOCs
```

The Pulse includes:

- IP addresses
- Domains
- URLs
- File hashes
- Related malware indicators

---

## Example Indicator Types

Possible IoC types include:

- FileHash ✅
- Domain
- IPv4
- IPv6
- URL
- Hostname

---

## Indicator Analysis

Selecting an indicator displays:

- Analysis Overview
- Related Pulses
- Associated malware
- Threat context
- Additional intelligence

This information helps analysts understand:

- Malware campaigns
- Threat relationships
- Attack infrastructure

---

## Searching Indicators

The lab demonstrates filtering indicators using keywords such as:

- Domain
- URL
- IPv4
- IPv6
- Hostname
- Hash

Filtering allows analysts to quickly locate specific IoCs.

---

# Common Threat Intelligence Sources

The lab introduces several widely used threat intelligence providers:

| Source | Purpose |
|---------|----------|
| CISA | Government cybersecurity advisories |
| NIST CSRC | Security standards and guidance |
| FBI InfraGard | Threat sharing community |
| SANS Internet Storm Center | Internet attack monitoring |
| VirusTotal Intelligence | Malware and file reputation |
| Cisco Talos | Threat intelligence |
| Spamhaus | Spam and malicious IP reputation |
| CrowdStrike Intelligence | Commercial threat intelligence |
| AlienVault OTX | Community IoCs |
| Anomali ThreatStream | Threat intelligence platform |
| Mandiant Threat Intelligence | Advanced threat research |
| Abuse.ch | Malware tracking |
| ThreatFeeds.io | Open-source threat feeds |

---

# Threat Intelligence Benefits

Threat feeds enable organizations to:

- Detect known malicious IPs
- Block malicious domains
- Improve SIEM alerts
- Perform threat hunting
- Reduce response time
- Stay informed about emerging threats

---

# Part 2 — Exploring Exploit Database

The second portion of the lab examines the **Exploit Database (Exploit-DB)**.

Exploit-DB is maintained by:

> **Offensive Security**

It provides:

- Public exploits
- Proof-of-concept (PoC) code
- CVE references
- Vulnerability research
- Security papers

---

# Exploit Database Information

Each exploit entry contains:

| Field | Description |
|---------|-------------|
| Date | Publication date |
| Download | Exploit source code |
| Vulnerable Application | Target software |
| Verified | Whether the exploit has been verified |
| Title | Exploit description |
| Type | Local, Remote, DoS, WebApp |
| Platform | Windows, Linux, PHP, etc. |
| Author | Exploit creator |

---

# Filtering Exploits

The Exploit Database supports filtering by:

- Type
- Platform
- Author
- Port
- Tags

This makes locating relevant exploits significantly easier.

---

# Google Hacking Database (GHDB)

The lab also introduces the:

> **Google Hacking Database (GHDB)**

GHDB contains Google search operators ("Google Dorks") used to identify:

- Exposed files
- Sensitive documents
- Login portals
- Configuration files
- Password files
- Publicly accessible vulnerabilities

---

## Example GHDB Categories

Examples include:

- Files Containing Passwords
- Login Portals
- Sensitive Directories
- Error Messages
- Database Dumps
- Configuration Files

---

# Google Dorking Warning

The lab emphasizes that Google Dorking should only be performed:

- On authorized systems
- For defensive purposes
- Inside hardened environments or virtual machines

This helps reduce exposure to potentially malicious websites.

---

# Additional Exploit-DB Resources

The Exploit Database also includes:

- Security Papers
- Shellcodes
- SearchSploit Manual
- Google Hacking Database (GHDB)

These resources support vulnerability research and penetration testing.

---

# Key Concepts Learned

## Indicators of Compromise (IoCs)

Examples include:

- IP addresses
- Domains
- URLs
- File hashes
- Hostnames

---

## Threat Intelligence

Threat intelligence helps organizations:

- Detect attacks
- Investigate incidents
- Improve threat hunting
- Strengthen defenses
- Enhance SIEM detection

---

## Exploit Database

Provides:

- Public exploits
- Proof-of-concept code
- Vulnerability details
- CVE references
- Exploit verification

---

## Google Hacking Database

Used to locate:

- Publicly exposed sensitive information
- Misconfigured systems
- Vulnerable web resources

---

# Skills Practiced

- Threat intelligence research
- Indicator of Compromise analysis
- Threat feed exploration
- Vulnerability research
- Exploit analysis
- Google Dorking awareness
- Vulnerability management

---

# Security Takeaways

- Threat intelligence feeds improve proactive defense.
- IoCs enable faster detection and investigation of attacks.
- Exploit Database helps defenders understand publicly available exploits.
- Google Dorking can reveal exposed assets and should only be used ethically.
- Continuous vulnerability management is critical to reducing organizational risk.

---

## Technologies & Resources

- AlienVault OTX
- CIS Threat Feeds
- Exploit Database (Exploit-DB)
- Google Hacking Database (GHDB)
- VirusTotal
- Cisco Talos
- CrowdStrike Intelligence
- Mandiant
- CISA
- NIST
- SANS Internet Storm Center
- Abuse.ch
- ThreatFeeds.io

---

## Lab Outcome

Successfully explored multiple threat intelligence sources, analyzed Indicators of Compromise (IoCs), researched public exploits using Exploit Database, examined Google Hacking Database techniques, and gained practical knowledge of vulnerability management resources used by cybersecurity professionals. :contentReference[oaicite:0]{index=0}
```
