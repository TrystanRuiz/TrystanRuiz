# Trystan Ruiz

[Portfolio](https://trystanruiz.tech) | [LinkedIn](https://linkedin.com/in/trystanruiz)

UCF IT student focused on cybersecurity, SIEM, SOC operations, and homelab infrastructure. Building hands-on projects in AI-powered security tooling, Splunk, honeypot pipelines, Linux hardening, and incident analysis. CompTIA Security+ certified, Network+ and CySA+ in progress.

Seeking cybersecurity / SOC analyst / security operations internships where I can contribute in monitoring, detection, triage, and hands-on lab work.

## AI Security Tools

- **[ThreatScope](https://github.com/TrystanRuiz/ThreatScope)** - Local-first AI-powered SOC triage tool built in Python. Parses phishing emails and security alerts, extracts and defangs IOCs, enriches indicators against VirusTotal, AbuseIPDB, MalwareBazaar, and NVD, maps findings to 20 MITRE ATT&CK techniques with confidence scoring, and generates investigation reports via a local LLM running through Ollama. No data leaves the machine.

## Honeypot & SIEM

- **[Honeypot Threat Pipeline](https://github.com/TrystanRuiz/honeypot-threat-pipeline)** - T-POT Standard on Proxmox with 21 sensors capturing 762k+ events from 115 unique IPs. Built a Python pipeline that pulls attacker IPs from Elasticsearch, scores them against AbuseIPDB, and auto-pushes blocks to OPNsense via REST API. Rewrote it in async Python and cut check time by 76%. Includes standalone Cowrie SSH honeypot with Splunk SIEM integration, Hydra brute-force simulation, and network hardening with UFW and Fail2Ban.

- **[Splunk SIEM Environment](https://github.com/TrystanRuiz/Splunk-Sysmon-SIEM)** - Self-hosted Splunk Enterprise ingesting Windows Security events and Sysmon telemetry. Built SOC dashboards tracking LOLBin abuse, encoded PowerShell, lsass access attempts, and brute force patterns, all mapped to MITRE ATT&CK technique IDs.

## SOC & Incident Response

- **[SOC Writeups](https://github.com/TrystanRuiz/SOC-Writeups)** - Alert triage, phishing analysis, and incident report writeups from TryHackMe and LetsDefend simulated SOC environments.

## Infrastructure

- **[HomeLab](https://github.com/TrystanRuiz/HomeLab)** - Proxmox VE running 7 LXC containers and 2 VMs including Splunk, Grafana/Prometheus, Gitea, Authelia SSO, and Nginx Proxy Manager. Kali and Windows VMs for attack simulation, with Tailscale subnet routing for remote access.

## Technical Skills

Splunk, Sysmon, Ollama, Streamlit, VirusTotal API, AbuseIPDB, MalwareBazaar, MITRE ATT&CK, Cowrie, T-POT, Suricata, ELK Stack, Python, asyncio, aiohttp, OPNsense, Hydra, UFW, Fail2ban, Proxmox, Linux, Windows Server, Grafana, Prometheus, Tailscale, log analysis, alert triage, incident reporting, blue team operations
