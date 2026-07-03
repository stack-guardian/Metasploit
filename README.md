# Metasploit Research

Structured documentation of my Metasploit Framework study, lab work, and exploitation research. This repository covers the full offensive lifecycle — from initial reconnaissance through post-exploitation and lateral movement — using Metasploit as the primary framework. All activity was conducted in authorized lab environments including Hack The Box, TryHackMe, and self-hosted vulnerable machines.

The goal is not a collection of screenshots. It is a working reference that reflects how I think through engagements: what the tool is doing under the hood, why a particular module or payload choice matters, and what the output actually means in context.

---

## Scope and Environment

All research documented here was performed in isolated, authorized environments. No production systems or live targets were involved. Lab environments used:

- Hack The Box (retired machines)
- TryHackMe (offensive learning paths)
- DVWA — Damn Vulnerable Web Application
- WebGoat
- VulnHub machines (local VirtualBox/VMware)
- Custom Kali Linux attacker VM

Framework version: Metasploit Framework 6.x  
OS: Kali Linux (rolling)

---

## Repository Structure

```
metasploit-research/
├── README.md                          -- This file
├── PROGRESS.md                        -- Daily activity log
│
├── 01-fundamentals/                   -- Core framework mechanics and command reference
├── 02-reconnaissance/                 -- Active and passive recon using Metasploit
├── 03-exploitation/                   -- Exploitation reports from HTB and lab machines
├── 04-payloads-and-meterpreter/       -- Payload architecture and Meterpreter usage
├── 05-post-exploitation/              -- Privilege escalation, persistence, credential harvesting
├── 06-web-application-exploitation/   -- DVWA, WebGoat, and web-focused modules
├── 07-custom-modules/                 -- Custom Ruby modules written from scratch
├── 08-evasion-and-encoding/           -- Encoder usage, AV evasion, obfuscation techniques
├── 09-full-engagements/               -- End-to-end engagement documentation
└── cheat-sheets/                      -- Compact operational reference sheets
```

---

## Coverage Summary

| Section | Topic | Status |
|---|---|---|
| 01 | Framework fundamentals and msfconsole | Complete |
| 02 | Reconnaissance and db_nmap workflows | Complete |
| 03 | Exploitation — HTB Lame, Legacy, Blue | Complete |
| 04 | Payload types, staged vs stageless, Meterpreter | Complete |
| 05 | Post-exploitation — privesc, persistence, creds | Complete |
| 06 | Web application exploitation via Metasploit | Complete |
| 07 | Custom module development in Ruby | In Progress |
| 08 | Evasion, encoding, and AV bypass techniques | In Progress |
| 09 | Full end-to-end engagement chains | In Progress |
| -- | Cheat sheets | Complete |

---

## Machines Documented

| Machine | Platform | OS | Vulnerability | CVE |
|---|---|---|---|---|
| Lame | Hack The Box | Linux | Samba usermap_script | CVE-2007-2447 |
| Legacy | Hack The Box | Windows XP | MS08-067 NetAPI | CVE-2008-4250 |
| Blue | Hack The Box | Windows 7 | EternalBlue / MS17-010 | CVE-2017-0144 |

---

## Skills Demonstrated

Metasploit Framework operation at the module and API level. Understanding of exploit development context — not just running searchsploit and use, but knowing why the exploit works, what the shellcode is doing, and what conditions cause it to fail. Payload staging mechanics, encoder selection, Meterpreter post-exploitation scripting, and custom module development in Ruby.

Reconnaissance-to-exploitation-to-post-exploitation chains documented end-to-end with enough detail to reproduce each step from scratch.

---

## Background

B.Tech in Cyber Security, LNCT Group of Colleges, Bhopal, India. Expected graduation June 2027.  
Certified Network Security Practitioner (CNSP) — 85%.  
PortSwigger Web Security Academy — 161 labs completed across 17 vulnerability classes.  
Bug bounty research via BugV platform.

GitHub: https://github.com/stack-guardian  
LinkedIn: https://www.linkedin.com/in/vibhor-prasad-3ba373381/  
Contact: vibhorprasad14@gmail.com

---

## Legal

All research in this repository was conducted exclusively in authorized lab environments. No real-world targets, production systems, or systems without explicit authorization were involved. This repository is published for educational documentation purposes only.
