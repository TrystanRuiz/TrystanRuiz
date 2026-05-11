# Trystan Ruiz

[Portfolio](https://trystanruiz.tech) | [LinkedIn](https://linkedin.com/in/trystanruiz)

UCF IT student focused on cybersecurity, SIEM, SOC operations, and homelab infrastructure. Building hands-on projects in AI-powered security tooling, Splunk, honeypot pipelines, Linux hardening, and incident analysis. CompTIA Security+ certified, Network+ and CySA+ in progress.

Seeking cybersecurity / SOC analyst / security operations internships where I can contribute in monitoring, detection, triage, and hands-on lab work.

## AI Security Tools

- **[TriageAI](https://github.com/TrystanRuiz/TriageAI)** - Local-first AI-powered SOC triage tool built in Python. Parses phishing emails and security alerts, extracts and defangs IOCs, enriches indicators against VirusTotal, AbuseIPDB, MalwareBazaar, and NVD, maps findings to 20 MITRE ATT&CK techniques with confidence scoring, and generates investigation reports via a local LLM running through Ollama. No data leaves the machine.

## Active Directory & SIEM

- **[Active Directory Security Lab](https://github.com/TrystanRuiz/ad-security-monitoring-hardening-lab)** - Built a Windows domain (BLUECORP.local) on Proxmox with a DC, file server, Sysmon, and Splunk SIEM. Simulated 7 attack scenarios mapped to MITRE ATT&CK, investigated each in Splunk, and hardened the domain via Group Policy. 4 incident reports with full evidence.

- **[Splunk SIEM Environment](https://github.com/TrystanRuiz/Splunk-Sysmon-SIEM)** - Self-hosted Splunk Enterprise ingesting Windows Security events and Sysmon telemetry. Built SOC dashboards tracking LOLBin abuse, encoded PowerShell, lsass access attempts, and brute force patterns, all mapped to MITRE ATT&CK technique IDs.

## Honeypot & Threat Intelligence

- **[Honeypot Threat Pipeline](https://github.com/TrystanRuiz/honeypot-threat-pipeline)** - T-POT on Proxmox capturing 762k+ events across 21 sensors. Built a Python pipeline that scores attacker IPs against AbuseIPDB and auto-pushes blocks to OPNsense via REST API. Includes standalone Cowrie SSH honeypot with Splunk integration and network hardening with UFW and Fail2Ban.

## SOC & Incident Response

- **[SOC Writeups](https://github.com/TrystanRuiz/SOC-Writeups)** - Alert triage, phishing analysis, and incident report writeups from TryHackMe and LetsDefend simulated SOC environments.

## Infrastructure

- **[HomeLab](https://github.com/TrystanRuiz/HomeLab)** - Proxmox VE running 7 LXC containers and 2 VMs including Splunk, Grafana/Prometheus, Gitea, Authelia SSO, and Nginx Proxy Manager. Kali and Windows VMs for attack simulation, with Tailscale subnet routing for remote access.
